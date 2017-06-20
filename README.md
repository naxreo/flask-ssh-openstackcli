*naxreo/flask-ssh*

1. based on ubuntu 16.04
2. installed openssh-server with password 'root/root'
3. installed nginx-full
4. installed uwsgi and flask by pip
5. tzdata is 'Asia/Seoul'
6. run supervisord and logs out /dev/stdout or stderr
7. install openstackclient cli by pip

example)
docker run -it -p 80:80 -p 22:22 -p 443:443 -e TZ='Asia/Seoul' --name flask naxreo/flask-ssh
