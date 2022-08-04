# Fly.io build issue

Reproduce with:

```
$ DOCKER_BUILDKIT=1 docker build --build-arg BUNDLER_VERSION="2.3.19" --build-arg NODE_VERSION="14" --build-arg RUBY_VERSION="2.7.6" --progress=plain -t app .
```

