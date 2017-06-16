# docker

	
RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y ntp
    
    ntpd -gq
service ntp start
