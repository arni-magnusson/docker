FROM       r-base:4.3.0
MAINTAINER Arni Magnusson
COPY       .Rprofile .
RUN        apt-get update \
             && apt-get install -y --no-install-recommends \
             cmake
RUN        Rscript -e "install.packages('sdmTMB')"
