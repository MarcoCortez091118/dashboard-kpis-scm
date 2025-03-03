## Manual Build 

> 👉 Download code

```bash
$ git clone https://github.com/app-generator/rocket-flask.git
$ cd rocket-flask
```

> 👉 Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

> 👉 Install **Tailwind/Flowbite** (another terminal)

Tested with **Node** `v18.20.0` (use at least this version or above)

```bash
$ npm install
$ npm run dev    # DEVELOPMENT (LIVE reload)
$ npm run build  # PRODUCTION
```

> 👉 Start [Rocket Flask](https://appseed.us/product/rocket/flask/) Starter

```
$ flask run 
```

<br />

## Start With Docker

> Download code

```bash
$ git clone https://github.com/app-generator/rocket-flask.git
$ cd rocket-flask
```

> Start with Docker Compose

```bash
$ docker-compose up --build 
``` 

Visit the app in the browser `localhost:5085`.
