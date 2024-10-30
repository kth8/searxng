SearXNG Docker image with configuration files included so it can be deployed without a host volume mount.
```
services:
  searxng:
    image: ghcr.io/kth8/searxng:latest
    container_name: searxng
    ports:
      - "8080:8080"
    restart: always
```
https://docs.openwebui.com/tutorials/features/web_search/
