# HumbleCyton

How to run:
1. docker build -t humble_cyton .
2. docker run -it --user ros --network=host --ipc=host -v /tmp/.X11-unix:/tmp/.X11-unix:rw --env=DISPLAY --env="QT_X11_NO_MITSHM=1" --device=/dev/dri:/dev/dri humble_cyton


