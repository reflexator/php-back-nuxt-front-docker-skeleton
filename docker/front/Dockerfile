FROM node:14.2-alpine

ENV NODE_ENV=development
ENV HOST 0.0.0.0

WORKDIR "/app"

### Locales
ENV ALLOWED_LANGUAGES="cs"
ENV DEFAULT_LANGUAGE="cs"

EXPOSE 3000

CMD ["yarn", "run", "dev"]
