#使うDockerイメージ
FROM  mysql:8.0
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./database/my.cnf /etc/mysql/conf.d/my.cnf

#docker runに実行される
CMD ["mysqld"]