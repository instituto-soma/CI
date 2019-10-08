FROM laradock/workspace:2.2-7.1

RUN apt-get update -qq
RUN apt-get install -y -f \ 
  libldap2-dev \
  unzip \
  php7.1-ldap 
RUN apt-get clean