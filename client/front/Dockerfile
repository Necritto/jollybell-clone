FROM node:16.16.0-alpine3.16

ENV APP_ROOT /front

WORKDIR ${APP_ROOT}

#RUN apk add curl git && chown -R node:node ${APP_ROOT}
# USER node

# COPY --chown=node:node package.json ./package.json
# COPY --chown=node:node yarn.lock ./yarn.lock
# RUN yarn install --frozen-lockfile

# COPY next.config.js ./next.config.js

CMD ["yarn", "dev"]
