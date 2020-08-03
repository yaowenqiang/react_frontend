FROM nginx
RUN  echo deb http://mirrors.aliyun.com/debian/ stretch main non-free contrib >>/etc/apt/sources.list
RUN  echo deb-src http://mirrors.aliyun.com/debian/ stretch main non-free contrib >>/etc/apt/sources.list
RUN  echo deb http://mirrors.aliyun.com/debian-security stretch/updates main >>/etc/apt/sources.list
RUN  echo deb-src http://mirrors.aliyun.com/debian-security stretch/updates main >>/etc/apt/sources.list
RUN  echo deb http://mirrors.aliyun.com/debian/ stretch-updates main non-free contrib >>/etc/apt/sources.list
RUN  echo deb-src http://mirrors.aliyun.com/debian/ stretch-updates main non-free contrib >>/etc/apt/sources.list
RUN  echo deb http://mirrors.aliyun.com/debian/ stretch-backports main non-free contrib >>/etc/apt/sources.list
RUN  echo deb-src http://mirrors.aliyun.com/debian/ stretch-backports main non-free contrib >>/etc/opt/sources.list
RUN apt-get update
COPY ./default.conf /etc/nginx/conf.d/
