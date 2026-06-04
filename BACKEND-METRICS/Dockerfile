FROM node:18-alpine
WORKDIR /app
RUN echo "console.log('Service Metrics pret pour Prometheus sur le port 5000'); setInterval(() => {}, 1000);" > server.js
EXPOSE 5000
CMD ["node", "server.js"]