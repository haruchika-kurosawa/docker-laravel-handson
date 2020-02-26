# base images
FROM mysql:8.0

# author
MAINTAINER marimo

# カスタムのcnfファイルを追加
# ここで書いているmy.cnfはおそらく同階層のmy.cnfを指している
ADD my.cnf /etc/mysql/conf.d/
# 権限の変更
RUN chmod 644 /etc/mysql/conf.d/my.cnf