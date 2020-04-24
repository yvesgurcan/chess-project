The idea is simple: Playing multiplayer chess in the browser.

The constraints:
- Running the application is 💯% free.
- As little as possible overhead to update the application.

And of course, we have all the features:
- Play against an AI.
- Play online or locally with other people.
- Play on a desktop computer, a tablet, or a mobile phone.
- Keep a history of your games.

Technically, this is what we use to make this feat happen:
- `chess-client`: A static website written in React and served via GitHub Pages.
- `chess-storage`: A GitHub repository to store game data.
- `chess-functions`: Multiple Netlify functions (aka Lambdas) to retrieve and save games.
- `chess-socket`: A websocket server hosted on Heroku to enable multiplayer.
