FROM debian:9

RUN apt-get -qq update && apt-get -y install gnupg curl

#
# Pull Zulu OpenJDK binaries from official repository:
#
#RUN echo "deb http://repos.azul.com/zing/debian stable main" >> /etc/apt/sources.list.d/zing.list
RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 0xB1998361219BD9C9 && \
    curl https://repos.azul.com/zing-fp/debian/zing.list > /etc/apt/sources.list.d/zing.list && \
    apt-get -qq update && \
    apt-get -y install zing-jdk11.0.0-fp && \
    rm -rf /var/lib/apt/lists/*

