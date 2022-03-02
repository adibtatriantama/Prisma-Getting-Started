# Prisma Getting Started

## Project Setup

1. Install dependencies

        npm install prisma typescript ts-node @types/node --save-dev
2. Setup tsconfig.json
3. Initiate Prisma

        npx prisma init
    This command does two things:

    - creates a new directory called prisma that contains a file called schema.prisma, which contains the Prisma schema with your database connection variable and schema models
    - creates the .env file in the root directory of the project, which is used for defining environment variables (such as your database connection)

## Connect your database

1. Modify prisma/schema.prisma
2. Set database url in .env
3. Define that we are using preview feature (Because MongoDB is currently a preview feature)

## Creating the Prisma Schema

1. See schema.prisma

## Install and generate Prisma Client

1. Install Prisma Client

        npm install @prisma/client

2. Generate Prisma

        prisma generate

![Prisma Client](https://res.cloudinary.com/prismaio/image/upload/v1628761155/docs/FensWfo.png)
