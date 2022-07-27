# hello-prisma
Quickstart Prisma NodeJS and Typescript

# Configurations
1 - npm init -y
2 - npm install typescript ts-node @types/node --save-dev
3 - touch tsconfig.json
4 - npm install prisma --save-dev
5 - npx prisma init --datasource-provider sqlite
6 - npx prisma migrate dev --name init
7 - touch script.ts
8 - npx ts-node script.ts