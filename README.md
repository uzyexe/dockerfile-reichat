# uzyexe/reichat

This is reichat container.

## What is reichat

reichat - A lovely paint chat application like a PaintChatApp built with Node.

[https://github.com/kanreisa/reichat](https://github.com/kanreisa/reichat)

## Dockerfile

[**Trusted Build**](https://hub.docker.com/r/uzyexe/reichat/)

This Docker image is based on the official [node:0.12.7-slim](https://registry.hub.docker.com/_/node) base image.

## How to use this image

```
docker run -p 10133:10133 uzyexe/reichat
```

### Help

```
  Usage: docker run -p 10133:10133 uzyexe/reichat [options]

  Options:
        Show this help message
            --help
        Show version and exit
            -v, --version
        Load a config file
            --config <value>
        Listening host
            --host <value>
        Listening port
            --port <value>
        Title of chat room
            --title <value>
        Width of canvas
            --canvas-width <value>
        Height of canvas
            --canvas-height <value>
        Redis host
            --redis-host <value>
        Redis port
            --redis-port <value>
        Redis password
            --redis-password <value>
            --redis-key-prefix <value>
        Data saving directory
            --data-dir <value>
            --data-file-prefix <value>
            --max-paint-log-count <value>
            --max-chat-log-count <value>
            --forwarded-header <value>
```
