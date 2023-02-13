# Next.js 13 + NextAuth.js Starter

This repository is a starter for building projects using Next.js 13, Prisma, and NextAuth.js with Google, Twitter, and magic links

## Installation

Use yarn to install the packages

```bash
yarn install
```

Create a .env file and fill it out at least with your Prisma DATABASE_URL

Create the database schema with Prisma Migrate and name the migration

```bash
npx prisma migrate dev
```

Generate the Prisma Client

```bash
npx prisma generate
```

## Usage

You can add or subtract providers as needed in ```[...nextauth].js```. Please see the documentation provided by [NextAuth.js](https://next-auth.js.org/) for more info about providers and special configurations, like custom emails

## Contributing

Pull requests and Issues are welcome!

## License

[MIT](https://choosealicense.com/licenses/mit/)