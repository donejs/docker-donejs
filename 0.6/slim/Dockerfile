# DoneJS 0.6
FROM node:4.2-slim

# DoneJS works best with npm version 2.x
RUN npm install -g npm@2.14

# Set environment variable for donejs version
ENV DONEJS_VERSION 0.6.0-pre.1

# Install latest version of DoneJS
RUN npm install -g donejs@v0.6.0-pre.1

CMD ["donejs"]
