ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/kibana/kibana:${ELK_VERSION}

# Add your kibana plugins setup here
# Install Wazuh-app in latest version for ELK 7.6.2
RUN kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-3.12.3_7.6.2.zip
