FROM  mcr.microsoft.com/dotnet/core/sdk:3.1
ENV HOME=/app/

ADD *tgz $HOME

WORKDIR $HOME/dotnetService

CMD ["dotnet", "run"]

EXPOSE 5001
