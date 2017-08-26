FROM circleci/node:8.4.0

# Install yarn v0.27.5
RUN (cd /tmp && curl -sSL 'https://github.com/yarnpkg/yarn/releases/download/v0.27.5/yarn-v0.27.5.tar.gz' | sudo tar xvzf -) && (sudo rm -fR /opt/yarn && sudo mv /tmp/dist /opt/yarn)
