FROM nginx:1.24.0
# イメージ作成時に実行するコマンド
RUN apt update
RUN apt install -y vim
COPY conf/nginx.conf /etc/nginx/
COPY conf/conf.d/default.conf /etc/nginx/conf.d/