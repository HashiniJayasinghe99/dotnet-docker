FROM mcr.microsoft.com/dotnet/aspnet:7.0
WORKDIR /App
COPY --from=build-env /build/out .
ENTRYPOINT ["dotnet", "DotNet.Docker.dll"]
ENV DOTNET_EnableDiagnostics=0