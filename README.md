# NGX-Error
A Container Repository that provides custom nginx error pages directly for your web server.

⚠ These Presets are done by [Pаramtamtām](https://github.com/tarampampam) please give his repositroy a star as well ⚠

## Road map

- [ ] More image variants (Apache Webserer, ...)
- [X] Ability to add your own Images

## Contributing

Do you want to share your own pack of various error screen?

Well open up a pull request and I'll add it. 😃


## Usage

Since we use "nginx:stable-alpine" as base image note that not all features are available.
To use your favorite preset just exchange your already existing image with one of these.

Just like this:

```yaml
  nginx:
    image: ghcr.io/its4nik/ghost:latest
    container_name: NGINX
    ports:
      - 80:80
    volumes:
      - ./nginx:/usr/share/nginx/html
```

Just have a look at all available variants here:

[Error-Pages](https://github.com/tarampampam/error-pages/tree/gh-pages)
