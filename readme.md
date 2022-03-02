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
