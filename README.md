# Docker  Getting Started Tutorial

This tutorial was written with the intent of helping folks get up and running
with containers and is designed to work with Docker Desktop. While not going too much 
into depth, it covers the following topics:

- [x] Running your first container
- [x] Building containers
- [x] Learning what containers are
- [x] Running and removing containers
- [x] Using volumes to persist data
- [x] Using bind mounts to support development
- [x] Using container networking to support multi-container applications
- [x] Using Docker Compose to simplify the definition and sharing of applications
- [x] Using image layer caching to speed up builds and reduce push/pull size
- [x] Using multi-stage builds to separate build-time and runtime dependencies

## Getting Started

If you wish to run the tutorial, you can use the following command after installing Docker Desktop:

```bash
docker run -d -p 80:80 docker/getting-started
```

Once it has started, you can open your browser to [http://localhost](http://localhost).

## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker compose up
```

## Contributing

If you find typos or other issues with the tutorial, feel free to create a PR and suggest fixes!

If you have ideas on how to make the tutorial better or want to suggest adding new content, please open an 
issue first before working on your idea. While we love input, we want to keep the tutorial scoped to new-comers.
As such, we may reject ideas for more advanced requests and don't want you to lose any work you might
have done. So, ask first and we'll gladly hear your thoughts!
