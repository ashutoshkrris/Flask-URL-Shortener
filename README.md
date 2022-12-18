# Flask URL Shortener

Flask URL shortener is a tool that takes any URL and generates a shorter, more readable version like bit.ly.

### Demo Video

Watch on YouTube: [https://www.youtube.com/watch?v=g6chXThUReU](https://www.youtube.com/watch?v=g6chXThUReU)

### Tutorials

* On freeCodeCamp: [https://www.freecodecamp.org/news/python-tutorial-how-to-create-a-url-shortener-using-flask/](https://www.freecodecamp.org/news/python-tutorial-how-to-create-a-url-shortener-using-flask/)
* On Hashnode: [https://ashutoshkrris.hashnode.dev/how-to-create-a-url-shortener-using-flask](https://ashutoshkrris.hashnode.dev/how-to-create-a-url-shortener-using-flask)

`.env` file contents:

```
SECRET_KEY=verysecretkey
DATABASE_URL=sqlite:///shorty.db
APP_SETTINGS=config.DevelopmentConfig
FLASK_APP=core
```

While deploying the app, make sure you change the `APP_SETTINGS` to `config.ProductionConfig`.
