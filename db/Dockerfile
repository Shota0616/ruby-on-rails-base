FROM mysql:8.2.0
COPY .bashrc .bashrc
# RUN apt update && apt install -y vim
# コンテナ実行時に実行されるコマンド
CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]