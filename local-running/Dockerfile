COPY --chown=node:node --chmod=755 package*.json ./
COPY --chown=node:node --chmod=755 ./src ./src
COPY --chown=node:node --chmod=755 ./configurations ./configurations

COPY --from=development /home/node/configurations ./configurations/
