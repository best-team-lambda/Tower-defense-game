# JS-Game-Dev-Testing

Setup instructions:
For local development pixi.js needs a server to be ran. Install this:
github repo: https://github.com/http-party/http-server
command line install: npm install http-server -g

Then run the server with http-server (path)
http-server "/c/Users/user/Documents/git/2 Best Team/JS-Game-Dev-Testing"
It will give you an ip where the server is live, so like 127.0.0.1:8080/index.html

Changes to code wont show up unless you clear your browser's cache/cookies.

Pixi.js setup is already done. You just download pixi.js and then add it with a <script> tag.

Linking to mainJS.js caused lots of undefined errors trying to do DOM manipulation until async was added to the script tag. This lets the HTML get loaded first I guess.

Looks like hosting on gh-pages doesn't require anything special to get it working.