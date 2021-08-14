# Demo Flask App

This is a Python Flask blog posting app from following Clever Programmer's [Python Flask Tutorial](https://www.youtube.com/watch?v=3mwFC4SHY-Y). This demo app implements a simple blog posting website.

I followed the video to understand how Python Flask works.

## Notes

1. Following the MVC (model view controller) web architecture, the model and controller both live in app.py. The view portion mainly resides in the /templates folder. To start running the app, run app.py.
2. Flask is typically used with Alchemy for database models. Pulling in Alchemy requires a small amount of work, because Flask is not not packaged with Alchemy by default.
3. The example routes used in the video seem RESTful-ish, but a bit backwards to me. But I just followed the video. I was here to learn flask, not nitpick on REST standards.