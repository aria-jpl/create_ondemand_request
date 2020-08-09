FROM hysds/pge-gdal:latest
#FROM hysds/pge-base:develop-es1

MAINTAINER HYSDS "hysds@jpl.nasa.gov"
LABEL description="PGE for on-demand request creation"

USER ops
COPY . /home/ops/verdi/ops/create_ondemand_request

# set entrypoint
WORKDIR /home/ops

CMD ["/bin/bash", "--login"]
