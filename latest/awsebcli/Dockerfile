FROM pistatium/docker-compose:latest

RUN pip install virtualenv && virtualenv cli && cli/bin/pip install awscli awsebcli

ENV PATH $PATH:/cli/bin
