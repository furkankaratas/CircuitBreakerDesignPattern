FROM microsoft/dotnet:3.0-aspnetcore-runtime AS base
WORKDIR /app
COPY /var/lib/docker/tmp/docker-builder301776510/GatewayApi .
ENTRYPOINT ["dotnet", "GatewayApi.dll"]