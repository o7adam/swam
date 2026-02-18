FROM node:22
RUN npm install -g openclaw
RUN npm install -g @vector-im/matrix-bot-sdk
CMD ["node", "/usr/local/lib/node_modules/openclaw/dist/index.js", "gateway", "--port", "8443"]
