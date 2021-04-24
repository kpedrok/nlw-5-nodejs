## Steps

- npm yarn init
- yarn add express
- yarn add @types/express -D
- yarn add typescript -D
- yarn tsc --init
- tsconfig -> Change "strict" to "false" remover uma verificacão redundante
- yarn add ts-node-dev -D

Banco
- typeorm init --name XXXX --database XXXX // not used, but could be
- yarn add typeorm
- yarn add sqlite3
- yarn add reflect-metadata
- yarn add uuid
- yarn add  @types/uuid -D
- yarn typeorm migration:create -n CreateSettings
- yarn typeorm migration:run     
- Por padrao horário é em UTC



# Other tools
- Postman
- BeeKeeper studio
