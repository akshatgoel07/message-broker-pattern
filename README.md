# Redis-cli in docker


1. Start Redis Docker container:

   ```bash
   docker run --name my-redis -d -p 6379:6379 redis

2. To connect to the Redis container:

   ```bash
   docker exec -it container_id /bin/bash

3. To access the CLI:

   ```bash
   redis-cli
