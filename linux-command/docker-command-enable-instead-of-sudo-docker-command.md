Make sure your user is part of the "docker" group. Run the following command in your terminal:

`sudo usermod -aG docker $USER`


ensure that the Docker daemon socket file has the correct permissions:

`sudo chmod 666 /var/run/docker.sock`