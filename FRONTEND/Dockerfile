FROM node:18-alpine AS build
WORKDIR /app
RUN echo "// Simulateur Frontend GreenOps" > index.js

FROM nginx:alpine
COPY --from=build /app /usr/share/nginx/html
EXPOSE 80