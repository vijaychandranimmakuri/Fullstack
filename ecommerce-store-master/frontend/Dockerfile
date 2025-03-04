FROM node:20-alpine
WORKDIR /app
COPY package.json ./
RUN npm install --legacy-peer-deps  # This is the correct place for RUN
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
