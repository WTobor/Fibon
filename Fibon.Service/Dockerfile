FROM microsoft/dotnet:runtime

WORKDIR /dotnetapp

COPY ./bin/Docker .

ENV ASPNETCORE_ENVIRONMENT Docker

ENTRYPOINT dotnet Fibon.Service.dll