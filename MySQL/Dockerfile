FROM mcr.microsoft.com/mssql/server:2019-latest
WORKDIR /testapp
COPY myscript.sql ./
ENV ACCEPT_EULA=Y \
    SA_USER=$SQL_USER
ENV ACCEPT_EULA=Y \
    SA_PASSWORD=$SQL_PASS
EXPOSE 
CMD ["/opt/mssql/bin/sqlservr"]
