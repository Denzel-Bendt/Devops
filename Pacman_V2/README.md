# SL2B DevOps Project

![.NET CI](https://github.com/Denzel-Bendt/Devops/actions/workflows/dotnet.yml/badge.svg)

## Project Beschrijving
Dit project demonstreert DevOps praktijken voor het SL2A project.

## Hoe te gebruiken
1. Clone de repository
2. Bouw met `dotnet build`
3. Run tests met `dotnet test`

## Docker
```bash
docker build -t sl2b-devops .
docker run -it --rm sl2b-devops