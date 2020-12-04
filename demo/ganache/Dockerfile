FROM node:lts-alpine

RUN npm install -g ganache-cli

EXPOSE 8545
CMD [ "ganache-cli", "-d", "-h", "0.0.0.0", "--chainId", "5777" ]
