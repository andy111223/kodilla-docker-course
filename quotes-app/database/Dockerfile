FROM postgres:13

ENV POSTGRES_USER=kodilla
ENV POSTGRES_PASSWORD=kodilla
ENV POSTGRES_DB=kodilla-quotes

# Copy the SQL dump file to the container
# This dump file will be executed when the container starts
COPY dump.sql /docker-entrypoint-initdb.d
