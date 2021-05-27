# docker-avalanche

Runs an Avalanche full node inside a Docker container.

## Setup

- Make sure you have Docker and Docker Compose install.
- Use `git` to clone this repository and enter it.
- Create a `avax-data` directory.
- Start the full node with `docker-compose up -d`
- Monitor the node with `docker logs -f avax`

Full node data is saved to the `avax-data` directory. Edit the `volume` property of the `docker-compose.yml` file if you want to save the data to a different directory.

## License

[MIT](./LICENSE.md)
