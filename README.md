# 📦 Package Archive

Welcome to the **package-archive** repository! This repository serves as a backup source for Docker Hub images, providing alternative versions of packages in case they are removed or deprecated from Docker Hub.

## Available Packages

This repository currently hosts the following packages:

- [`cas`](https://github.com/HarryVasanth/package-archive/pkgs/container/cas)
- [`gitea`](https://github.com/HarryVasanth/package-archive/pkgs/container/gitea)
- [`graphql-engine`](https://github.com/HarryVasanth/package-archive/pkgs/container/graphql-engine)
- [`lib-js`](https://github.com/HarryVasanth/package-archive/pkgs/container/lib-js)
- [`node`](https://github.com/HarryVasanth/package-archive/pkgs/container/node)
- [`postgres`](https://github.com/HarryVasanth/package-archive/pkgs/container/postgres)

## Usage Instructions

You can use these images by pulling them directly from GitHub Packages. For example, to pull the [`gitea:1.16`](https://github.com/HarryVasanth/package-archive/pkgs/container/gitea/244901420?tag=1.16) image:

```bash
docker pull ghcr.io/harryvasanth/gitea:1.16
```

## Why Use This Repository?

- **Reliability**: Ensures access to specific package versions even if they're removed from Docker Hub
- **Consistency**: Maintains identical functionality to the original packages
- **Long-term availability**: Preserves critical dependencies for your projects

## License

Please refer to individual package documentation for specific licensing information.
