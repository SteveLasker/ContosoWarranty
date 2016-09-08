FROM microsoft/dotnet:1.0.0-core
ARG source=.
WORKDIR /app
COPY $source .
ENTRYPOINT dotnet PullClaims.dll
