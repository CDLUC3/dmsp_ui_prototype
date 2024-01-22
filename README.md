# dmsp_ui_prototype

This is the UI frontend to the new DMSP Prototype.

## Installation

### Rails API backend

You can run the Rails API backend locally (requires Docker and docker-compose) by:
- Cloning the [Rails repository](https://github.com/CDLUC3/dmsp_rails_prototype/)
- Checkout the version of the Rails app you want to work with, normally: `git fetch origin development && git checkout development`
- Startup the Docker container `docker-compose up`
- Update your local config to point to the local Rails API, normally: `http://localhost:3001`

To stop the container run `docker-compose down`
