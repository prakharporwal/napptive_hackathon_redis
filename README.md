# Redis

> Redis is an open-source, in-memory data structure store, used as a database, cache, and message broker. It supports a wide range of data structures, including strings, hashes, lists, sets, and sorted sets. Redis provides high performance and scalability, making it a popular choice for use cases such as real-time analytics, caching, and message queueing.

## Steps to deploy on Napptive via Web interface
- Click the "Deploy" button to the top right of the box .
- Add a name for the application deployment
- Select the environment you want to deploy to.
- Verify the Components Configuration (like  docker image version, cpu, memory usage, REDIS_PASSWORD)
- Click the deploy button and confirm.
- A new instance will be ready shortly in your environment.

### Warning
- Please update the REDIS_PASSWORD in envs of the OAM config while deploying for production environments.


## Steps to deploy on Napptive via CLI 
- Install the Napptive CLI command using https://docs.napptive.com/playground/cli/Installation.html.
- Use the command 
```
playground apps deploy prakharporwal99/redis:7.0 --env <account/env>
```
from your CLI
