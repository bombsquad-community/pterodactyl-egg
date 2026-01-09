# pterodactyl-egg
Use this to get an egg, not the kind u eat, the kind u put in pterodactyl panel to get a Bombsquad server

## How to configure the egg
- Select a nest or create a new one
- Create a new egg
- Enter the following info in the mentioned field
  - Docker Images: `ghcr.io/bombsquad-community/pterodactyl-egg/bombsquad_egg:latest`
  - Startup Command: `./ballisticakit_server`
  - Stop Command: `^C`
  - Log Configuration: `{}`
  - Configuration Files: `{}`
  - Start Configuration: `{}`
- Click "Create"

## How to get bombsquad server files
### Vanilla server
You can use [install-script.sh](install-script.sh) and paste in the "Install Script" tab in your egg to install the vanilla server
### Custom server scripts
You can use [install-script.sh](install-script.sh) and customize it to install custom server scripts
<br>or create a server without install scripts, and after starting it, manually upload the server files

