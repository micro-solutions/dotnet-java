FROM microsoft/dotnet:2.2-aspnetcore-runtime

# the below directory is missing and java would not install otherwise
RUN mkdir -p /usr/share/man/man1
RUN apt-get update
RUN apt-get install -y openjdk-8-jre