FROM markadams/chromium-xvfb-js

RUN apt-get update -y && apt-get install openssh-client -y
RUN eval $(ssh-agent -s)
RUN mkdir -p ~/.ssh
RUN chmod 700 ~/.ssh
RUN apt-get install git-core -y