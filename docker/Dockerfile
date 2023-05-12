FROM rocker/rstudio:latest-daily

RUN apt-get update -qq
RUN apt-get -y install git

RUN install2.r –error \
--deps TRUE \
rmarkdown
