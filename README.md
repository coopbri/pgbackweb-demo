# PG Back Web Demo

Docker Compose stack demonstrating [PG Back Web](https://github.com/eduardolat/pgbackweb) with local filesystem backups and MinIO for S3-API backups.

Video URL: https://youtu.be/UdvAmPoD2Y0

## Usage

- Spin up PG Back Web (service + database) as well as an example app database and a single-node MinIO server: `docker-compose up`

Note that this Compose file does not have production-ready settings for the services, it is just used to demonstrate how to use PG Back Web.

## License

MIT (see <a href="LICENSE.md">LICENSE.md</a>)
