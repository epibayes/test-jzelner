from jonzelner/docker-rstan

RUN apt-get update \ 
	&& apt-get install -y --no-install-recommends \
        libgdal-dev \
        libproj-dev
        
RUN install2.r --error \
    polyclip \
    maptools \
    deldir \
    pipeR \
    rgdal \
    regeos
