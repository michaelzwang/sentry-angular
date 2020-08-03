# sentry-angular

A simple Angular app with Sentry integrated to demonstrate Sentry error reporting.

When opening the app you should see a simple page with a 'Create Error' button.
![Sample App](/sample-app.png)

Once the button is clicked, it will fire an error which Sentry will detect. There will be a Sentry pop-up to notify the user.
![Sentry Pop-up](/sentry-popup.png)

In the Sentry UI, you can view the error under the project's 'Issues'.
![View Errors](/view-error.png)
