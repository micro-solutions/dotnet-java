# .NET Core + Java docker images

## Description

This repository contains docker images that combine both dotnet and java runtimes.
The images are based on the `microsoft/dotnet` image.

## Purpose

This image lets you use java tools inside an asp.net core web application.

## Naming Convention

Both the dotnet version and the java version are included in the tags.

The convention is as follows:

`microsolutions/dotnet-java:[dotnet-version]-[java-version]`

- `[dotnet-version]` is the tag from the `microsoft/dotnet` repository
Example: `2.2-aspnetcore-runtime`.

- `[java-version]` is the java version installed.
Example: `8-jre`.

## Available Tags

- `microsolutions/dotnet-java:2.2-aspnetcore-runtime-8-jre`