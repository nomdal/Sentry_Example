# NoahSentryExample

Pretty simple to run:

First, make sure to go into the "src.main.ts" file and put in your own Sentry dsn (right now it's mine). Save it. This will ensure the error message it throws gets sent to the right place.

1. Clone "git clone https://github.com/nomdal/Sentry_Example/"
2. "cd Sentry_Example"
3. May need to do "npm install --save @sentry/angular @sentry/tracing" or just "npm install" but should be fine since all the dependencies should be uploaded to the Github.
4. Run it with "ng serve --open"

Now it will open the locally hosted site in your browser. All you need to do is hit the button and it will call a function to generate an error, which will then be sent to your Sentry account that you previously linked.

Woo!
