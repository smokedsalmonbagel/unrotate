# unrotate

To build image clone unrotate repo, cd to unrotate/ directory, run:
docker build . -t image_name

windows:
docker run -it --rm -p 6080:80 -v "$pwd/:/root/Desktop" --name cv [image_name]

linux
sudo docker run -it --rm -p 127.0.0.1:6080:80 -v "$(pwd)/:/root/Desktop" --name cv [image_name


