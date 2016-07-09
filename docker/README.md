# Docker image of jupyter, imglib2 and notebooks

First you need to create the image from the docker file (not yet published to docker hub)
```shell
docker build -t j.cyriac/imglib2-notebooks-docker:v1
```

And after that you can run the image
```shell
docker run -t -i j.cyriac/imglib2-notebooks-docker:v1
```

To login to the image (for checking the file structute etc.)
```shell
docker run -t -i j.cyriac/imglib2-notebooks-docker:v1 /bin/bash
```


