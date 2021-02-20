# simple-static-startpage
A stupidly simple, static, startpage for selfhosted services.

## Usage

### Short version
Just put the /srv directory on a webserver somewhere.

### Less short version
Edit config.json with your services:
`vim config.json` 

Start the docker container:
`docker-compose up -d`

Browse to your startpage:
`open http://<your-ip>:8080`

## Screenshots
![Simple Static Startpage Desktop](/simple-static-startpage.png)

![Simple Static Startpage Mobile](/simple-static-startpage.gif)