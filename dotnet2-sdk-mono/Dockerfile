FROM microsoft/dotnet:2-sdk

RUN apt-get update && apt-get install -y apt-transport-https dirmngr
RUN apt-key adv --no-tty --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
RUN echo "deb https://download.mono-project.com/repo/debian stable-stretch main" > /etc/apt/sources.list.d/mono-official-stable.list
RUN apt-get update && apt-get install -y mono-devel
