# NFL Rushing

This is a solution to [nfl-rushing challenge](https://github.com/tsicareers/nfl-rushing) implemented by me (Shervin Khastoo). The backend is implemented using Elixir/Phoenix and the frontend is implemented using React.js. The backend and frontend projects are submodules of this repository.

## Cloning
To clone this project (including submodules) run:

```
git clone --recursive https://github.com/shervinkh/nfl_rushing.git
```

## Installation and running this solution
Assuming you have `docker` and `docker-compose` installed, you have access to docker hub, and ports 4000 and 8080 are open on your computer, run the following command to spawn the backend and frontend docker containers.

```
docker-compose up -d
```

After that, you can simply open [localhost:8080](http://localhost:8080) in your web browser.
