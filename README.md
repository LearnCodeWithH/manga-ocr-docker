# manga-ocr-docker

[Docker Hub](https://hub.docker.com/r/nanoskript/manga-ocr)
| [Demo](https://manga-ocr.nanoskript.dev/)

Docker service for <https://github.com/kha-white/manga-ocr>.

## Installation

```
docker run --publish $PORT:$PORT --env PORT=$PORT --detach nanoskript/manga-ocr
```

and navigate to 127.0.0.1:$PORT in your browser.

### CUDA Support

CUDA enabled image available as `nanoskript/manga-ocr-cuda`