FROM nitra/php

RUN yum install nodejs -y npm
RUN npm install -g ws

ADD run.sh /tmp/run.sh

CMD ["/bin/bash", "/tmp/run.sh"]
