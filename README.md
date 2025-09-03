# Open ScoreBoard Core.

## Status: Active Development

I am currently setting up this project.

### API:

#### Things i have done:

- Set up WebSocket server
- Implemented topic-based message routing
- Integrated Controller based routing using Hono and based on Laravel.
- Started with database design

#### Todo:

- Auth using better auth.
- Finish database design.
- Setting up routes
- Handeling websockets
- hockey.nl MatchCenter intergration.
- Way to store images/videos for sponsors and club logos and or animations for score, cards, etc.
- Add camera support for live streaming / showing cam on scoreboard ?

### Things this app will do:

clubs: sync clubs with hockey.nl, add clubs / import clubs.
teams: sync teams with hockey.nl, add teams / import teams.
matches: sync matches with hockey.nl, create matches using planner.
sponsorships: per match or screen saver or other.
As ref be able to controll scoreboard using the app manulay or using the connection with a live match thro hockey.nl

## This is build for MHCFlevoland using a led wall display. 
Will add other ways to connect to it later like micro controllers using websockets / api or WLED for led display using addressable rgb strip.
Or away for a score baord retrofit.

