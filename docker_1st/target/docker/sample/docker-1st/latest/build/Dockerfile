#
# Copyright (c) 2018 TIBCO Software Inc.
# 
ARG docker_base_version
FROM sbrt-base:10.5.0

LABEL description="StreamBase Application"

#
# Install application archive & test configurations
#
COPY maven ${RUNTIME_HOME}

#
# entry point to start node
#
ENTRYPOINT ${PRODUCT_HOME}/start-node
