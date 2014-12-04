FROM dduportal/fig:debian7
RUN apt-get update && apt-get install -y amqp-tools
ADD http://stedolan.github.io/jq/download/linux64/jq /usr/bin/jq
RUN chmod a+x /usr/bin/jq

