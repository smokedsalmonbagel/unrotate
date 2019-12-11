# unrotate

windows:
docker run -it --rm -p 6080:80 -v "$pwd/:/root/Desktop" --name cv tycon/opencvgui:latest

linux
sudo docker run -it --rm -p 6080:80 -v "~/:/root/Desktop" --name cv tycon/opencvgui:latest

