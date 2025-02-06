# 2025-02-04-docker

```
docker run --rm -it -e PASSWORD='password' -p 8787:8787 -v /$(pwd):/home/rstudio/work --platform=linux/amd64 rocker/rstudio:4.4.2
```

```bash
docker run \
    --rm \
    - it \
    -e PASSWORD = "password" \
    -p 8787:8787 \
    - v /$(pwd):/home/rstudio/work
    --platform=linux/amd64 
    rocker/rstudio:4.4.2
```
