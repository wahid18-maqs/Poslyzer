FROM node:20-slim
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5173
ENV HOST=0.0.0.0
ENV PORT=5173
CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0", "--port", "5173"]