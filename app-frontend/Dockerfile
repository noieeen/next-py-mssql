FROM node:latest
# RUN mkdir -p /usr/src/app
WORKDIR /app-frontend
COPY . .
RUN npm install
# COPY . /usr/src/app
EXPOSE 3000
CMD ["npm","run","production"]