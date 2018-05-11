# TileDB Library Test Project

This is a series of docker images to test the library install path of TileDB

This requires tiledb to be added to ./TileDB

## Build Debian Test Image

```
docker build -t tiledb-debian -f Dockerfile-debian .
```

## Build Fedora Test Image

```
docker build -t tiledb-fedora -f Dockerfile-fedora .
```

## Build Gentoo Test Image

```
docker build -t tiledb-gentoo -f Dockerfile-gentoo .
```
