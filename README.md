### rm-kws-interview-task

🎃 Bitcoin listing app created based on the requirements defined in [#1](https://github.com/reanimated-man/rm-kws-interview-task/issues/1)

This project was generated using [Nx](https://nx.dev).

### Stack

**Core**  
[Nx](https://nx.dev)

**Backend**  
[Nest.js](https://nestjs.com)  
[Fastify](https://www.fastify.io)  
[SQLite](https://www.sqlite.org/index.html)  
[Prisma](https://www.prisma.io)  
[Passport.js](https://www.passportjs.org)

**Frontend**  
[Next.js](https://nextjs.com)  
[Chakra UI](https://chakra-ui.com)

**Notes**

- SQLite can be scaled to distributed postgres if required.
- Prisma can be replaced with TypeORM if needed.

### DB Migrations

`pnpm prisma migrate <db_name> --name <any_migration_name>`

Example

```bash
pnpm prisma migrate dev --name init
```
