The idea is simple: Playing chess in the browser.

But the constraints are what makes this project interesting:
- Running the application is 💯% free.
- No overhead to update the application.

And of course, we have all the features:
- Play against an AI.
- Play online with other people.
- Play on a desktop computer, a tablet, or a mobile phone.
- Keep a history of your games.

Technically, this is what we use to make this feat happen:
- A static website written in React and served via GitHub Pages.
- A GitHub repository to store game data.
- Multiple Netlify functions (aka Lambdas) to retrieve and save games.
- A websocket hosted on Heroku to enable multiplayer.
