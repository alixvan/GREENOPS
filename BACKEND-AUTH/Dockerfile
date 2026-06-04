FROM node:18-alpine
WORKDIR /app
RUN echo "console.log('Service Auth JWT demarre sur le port 5000'); setInterval(() => {}, 1000);" > server.js
EXPOSE 5000
CMD ["node", "server.js"]