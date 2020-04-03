FROM wordpress

RUN apt-get -y update --fix-missing
RUN apt-get upgrade -y

# Install useful tools
RUN apt-get -y install apt-utils nano wget vim

RUN useradd --create-home -s /bin/bash -g www-data -G sudo -u 1000 docker

EXPOSE 80