# ProU Track 1&2&3

#### Submission By Aryansh Gupta - 22BCE10404
> ***Check Here : https://pro-u-frontend-theta.vercel.app/*** 

> ***Video Here : https://drive.google.com/file/d/1aFNo6-WyXJVtWWCYAcrbrCMMNVrxqfUK/view?usp=drive_link***

> Original Frontend Repo : https://github.com/aryanshdev/ProU-Frontend

> Original Backend Repo : https://github.com/aryanshdev/ProU-Backend

## Table of Contents

- [About](#about)
  - [System Architecture](#system-architecture)
  - [Screenshots](#screenshots)
  - [Technologies Used](#technologies-used)
- [Getting Started And Setup](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#1-backend)
  - [Frontend Setup](#2-frontend)
- [Features](#features)
- [Project Structure](#project-structure)
- [Submitted By](#submitted-by)

## About

I have created a Employee Management System for my submission in Track 1 & 2 & 3.<br />
The System Works on Both Mock Data (Track 1) and Actual Real Data stored in Database and Fetched via APIs (Track 2 & 3). 
### System Architecture
The Prototype is very simple and uses as fairly simple architecture. I given time I can also make this scalable by dividing the system into microservices and adding brokers like Kafka.

![System Architecture](./readme_imgs/sysarch.png)

### Screenshots

[**Video Demo Here**](https://drive.google.com/file/d/1aFNo6-WyXJVtWWCYAcrbrCMMNVrxqfUK/view?usp=drive_link)

![HomePage](./readme_imgs/homepage.png)


![Mockdata Dashbaord](./readme_imgs/mockdata.png)


![Adding Real User Page](./readme_imgs/addingEmp.png)

![Stats Page](./readme_imgs/stats.png)

![Real Options](./readme_imgs/options.png)

![Attendance Update](./readme_imgs/attendUpdate.png)


### Technologies Used

- **Frontend (Track 1 & 3)** : NextJS
- **Backend (Track 2 & 3)** : ExpressJS
- **Database (Track 2 & 3)** : PostgreSQL
- **Authentication (Bonus)** : Google OAuth, JWT
- **Deployement (Bonus)** : Render For Backend, Vercel For Frontend




## Getting started

These quick steps will get the project running locally. The repo contains two main folders: `frontend/` and `Backend/`.

#### Prerequisites
- Node.js 
- npm 
- PostgreSQL (only required for backend real-data mode)

#### 1) Backend

- cd into `Backend/`
- create a `.env` file (example values below) and ensure your Postgres connection is available.
	- Example `.env` values:
		- DATABASE_URL=postgres://user:password@localhost:5432/prou_db
		- PORT=5000
- install and run:

```bash
cd Backend
npm install
node server.js
```

#### 2) Frontend

- cd into `frontend/`
- install and run Next.js dev server:

```bash
cd frontend
npm install
npm run dev
```

Open http://localhost:3000 (frontend) and confirm the frontend can reach the backend API (if running).


## Features

- Dashboard with employee stats (mock & real data)
- Employee listing, add/edit/remove (Backend Required - **Track 2**)
- Authentication via Google OAuth + JWT (**Bonus**)
- Configurable to run in mock-mode (Frontend **Track 1**) or full API mode (**Track 3**)

## Project structure

- `frontend/` — Next.js app (pages, components, assets)
- `Backend/` — Express server, routes, DB connection
- `readme_imgs/` — images for this docs repo (system architecture)

## Submitted By

Author: Aryansh Gupta — 22BCE10404

Repo used for submissions.

---
