# Potato Disease Classification

## Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))

2. Install Python packages

```
pip3 install -r training/requirements.txt
pip3 install -r api/requirements.txt
```

3. Install Tensorflow Serving ([Setup instructions](https://www.tensorflow.org/tfx/serving/setup))

## Setup for ReactJS

1. Install Nodejs ([Setup instructions](https://nodejs.org/en/download/package-manager/))
2. Install NPM ([Setup instructions](https://www.npmjs.com/get-npm))
3. Install dependencies

```bash
cd frontend
npm install --from-lock-json
npm audit fix
```

4. Copy `.env.example` as `.env`.

5. Change API url in `.env`.


## Running the API

### Using FastAPI

1. Get inside `api` folder

```bash
cd api
```

2. Run the FastAPI Server using uvicorn

```bash
uvicorn main:app --reload --host 0.0.0.0
```

3. Your API is now running at `0.0.0.0:8000`


## Running the Frontend

1. Get inside `api` folder

```bash
cd frontend
```

2. Copy the `.env.example` as `.env` and update `REACT_APP_API_URL` to API URL if needed.
3. Run the frontend

```bash
npm run start
```

## You shall now be able to upload a picture of a leaf into the frontend and check how it classifies#   P o t a t o - d i s e a s e - c l a s s i f i c a t i o n  
 