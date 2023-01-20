# Learn English

This project comprises 2 repositories
- Backend (Rails): https://github.com/Vishwas-N-Developer/learnEnglish
- Frontend (React): https://github.com/Vishwas-N-Developer/learn-english-frontend.git

## Installation

This project requires [Docker](https://docs.docker.com/get-docker/) to run.

Use the following command to clone this repository.
This command will clone this repository with the frontend & backend repositories as submodules as well.
```sh
git clone https://github.com/Vishwas-N-Developer/learn-english.git --recurse-submodules
```

Navigate to Application Directory
```sh
cd learn-english.git
```

## Testing

Run following command to check if the test cases are passing.

```sh
docker-compose run backend rspec
```

## Running the Application

Run following command to start the Backend Server (http://localhost:3001) & Frontend Server (http://localhost:3000).

```sh
docker-compose up --build
```

Verify the application is running by navigating to your server address in
your preferred browser.

```sh
localhost:3000
```

## Repositories

- [Backend](https://github.com/Vishwas-N-Developer/learnEnglish)
- [Frontend](https://github.com/Vishwas-N-Developer/learn-english-frontend)

## Thanks
