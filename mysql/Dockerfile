FROM mysql:8.4.3
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
ADD scripts/*.sql /docker-entrypoint-initdb.d
    # MYSQL_DATABASE=transations \
    # MYSQL_USER=expense \
    # MYSQL_PASSWORD=ExpenseApp@1