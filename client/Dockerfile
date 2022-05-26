FROM ubuntu:latest
RUN apt update && apt install -y curl
RUN curl https://download.splunk.com/products/universalforwarder/releases/8.2.6/linux/splunkforwarder-8.2.6-a6fe1ee8894b-linux-2.6-amd64.deb -o splunk.deb
RUN dpkg -i splunk.deb && rm splunk.deb
CMD tail -f /dev/null