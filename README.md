# Application Package Registry Setup

### Requirements
- Docker Engine
- Docker Compose

### Setup
1. Clone this repository to your execution environment;
   
2. Edit file **pygeoapi.config.yml**,
   Mandatory update: the `url` property inside the `server` class:
```yaml
server:
  url: 
```
  Optional update: All properties inside the `metadata` class:
```yaml
metadata:

```

3. Open a command line console in the same folder where the repository was cloned and execute:
```bash
docker-compose up
```

It should start the two services that are defined in the `docker-compose.yml` file: registry and elastic_search.
