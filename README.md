# GabyRoos.com - Version 2

Put together using the amazing static site generator [Hugo](https://gohugo.io/)!

## Running locally/development

```bash
hugo run server
```

## Running in Docker

Build the static site:
```bash
hugo --minify --verbose
```

```bash
docker build -t gabyroosdotcom:latest .
docker run --rm -p 8020:80 gabyroosdotcom:latest
```

## Licence

The **code** in this repo is licensed under the MIT license.

**Image** and **video** may be subject to Copyright.

## Sources/References

* https://realfavicongenerator.net/ for generating all the favicons in an easy to use format