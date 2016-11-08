FROM postgres:9.4

RUN sed -i "s@#log_statement = 'none'@log_statement = 'all'@" /usr/share/postgresql/$PG_MAJOR/postgresql.conf.sample

