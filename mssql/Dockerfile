FROM mcr.microsoft.com/mssql/server:2017-latest-ubuntu

ENV MSSQL_PID=Express
ENV MSSQL_COLLATION="SQL_Latin1_General_CP1256_CI_AS"
ENV MSSQL_DATABASE=$MSSQL_DATABASE
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=$MSSQL_PASSWORD

VOLUME /var/opt/mssql

EXPOSE 1433
