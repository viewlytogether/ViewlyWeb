FROM oven/bun:edge

WORKDIR /app

COPY . .

RUN bun install

CMD ["bun", "run", "src/index.ts"]