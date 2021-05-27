# publish-image

https://github.com/gliptak?tab=packages

https://docs.github.com/en/actions/guides/publishing-docker-images

https://github.com/opencontainers/image-spec/blob/master/annotations.md

https://github.com/marketplace/actions/publish-docker-image

```
docker run --rm -v ~/.aws:/root/.aws -v $(pwd):/app -v $(pwd)/site-packages:/usr/lib/python3.8/site-packages/ ghcr.io/gliptak/publish-image:latest --version
```
