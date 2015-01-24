# base
#
# VERSION               0.0.2

FROM     ubuntu:14.04
MAINTAINER Andres F. Lamilla, "alamilla@gmail.com"

# se actualiza la base de datos de apt
RUN apt-get update -qq #22/06/2014

# instalacion de los paqutes necesarios
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y supervisor git wget unzip
