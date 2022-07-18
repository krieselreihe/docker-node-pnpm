FROM circleci/node:16.13.1

RUN curl -f https://get.pnpm.io/v6.16.js | sudo node - add --global pnpm@7
RUN pnpm config set store-dir ~/.pnpm-store
