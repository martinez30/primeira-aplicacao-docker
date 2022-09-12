FROM bitnami/dotnet-sdk:3.1

ENV PATH $PATH:/$HOME/.dotnet/tools

RUN dotnet tool install --global dotnet-ef --version 3.1

COPY ./ /opt/dotnet

WORKDIR /opt/dotnet

RUN dotnet restore

EXPOSE 5000 

CMD dotnet run --project DockerMinicurso