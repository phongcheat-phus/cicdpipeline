FROM directus/directus:11.4.1
USER root
RUN pnpm --version || npm install -g pnpm
USER node
RUN pnpm install directus-extension-schema-management-module
