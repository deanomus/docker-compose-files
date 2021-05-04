#[docker-volume-backup](https://hub.docker.com/r/futurice/docker-volume-backup/)

Docker-volume-backup is an Docker image for performing simple backups of Docker volumes. Main features:

- Mount volumes into the container, and they'll get backed up
- Use full `cron` expressions for scheduling the backups
- Backs up to local disk, [AWS S3](https://aws.amazon.com/s3/), or both
- Allows triggering a backup manually if needed
- Optionally stops containers for the duration of the backup, and starts them again afterward, to ensure consistent backups
- Optionally `docker exec`s commands before/after backing up a container, to allow easy integration with database backup tools, for example
- Optionally ships backup metrics to [InfluxDB](https://docs.influxdata.com/influxdb/), for monitoring
- Optionally encrypts backups with `gpg` before uploading


## Setup
1. Copy example env file:
    - ```cp .env.example .env```
2. Configure the .env file:
    - ```vim .env``` or ```nano .env```
3. (Optionally) adjust the docker compose file for your needs
4. Spin up docker-volume-backup:
    - ```docker-compose up -d```
    
    
## How to trigger a backup manually:
- ```docker-compose exec backup ./backup.sh```