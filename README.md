# unrotate

windows:
docker run -it --rm -p 6080:80 -v "$pwd/:/root/Desktop" --name cv [image tag]

linux
sudo docker run -it --rm -p 127.0.0.1:6080:80 -v "$(pwd)/:/root/Desktop" --name cv [image tag]

