# docker-xmrig

A docker container for [xmrig](https://github.com/xmrig/xmrig), including donate level patch.

## Requirements

 * [docker](https://docs.docker.com/install/)

## Usage

### First

Pull the latest build:

```
docker pull bananajamma/xmrig
```

### Running

Example:

```
docker run -it --rm --name xmrig bananajamma/xmrig --donate-level 0 -o gulf.moneroocean.stream:10032 -u 4JLN35ooAiU15BX6Rzi6DTWUKsdLALvf6Stx1uLLrYP28scYTAtyjhM3ULkrpCQMQ1BGvn2hSaYGtSzwtPcZhFSwdoFypnBsb6wKfhTGix -p x -k
```

### Building

If you've clone this repo and made changes:

```
docker build . --tag bananajamma/xmrig
```

## License

MIT
