
FROM node:20

WORKDIR /app
COPY . .

RUN npm install
RUN npm run build

EXPOSE 3000
CMD ["npm", "run", "preview", "--", "--host", "--port", "3000"]
