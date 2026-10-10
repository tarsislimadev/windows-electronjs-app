FROM electronuserland/builder:wine

WORKDIR /app

COPY . .

RUN npm ci

COPY . .

RUN npm run build
