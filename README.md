

### 🚀 Getting Started
```
1. Install dependencies
Navigate to the project directory:
```shell

```
Then install the necessary packages:
```shell
npm install
```
2. Setup environment variables
Create a .env file in the root directory and add the following:

```js
DATABASE_URL=YOUR_MONGODB_CONNECTION_STRING
GOOGLE_CLIENT_ID=YOUR_GOOGLE_CLIENT_ID
GOOGLE_CLIENT_SECRET=YOUR_GOOGLE_CLIENT_SECRET
GITHUB_ID=YOUR_GITHUB_ID
GITHUB_SECRET=YOUR_GITHUB_SECRET
NEXTAUTH_SECRET=RANDOM_STRING_SECRET
CLOUDINARY_URL=YOUR_CLOUDINARY_URL
```
Replace placeholders (YOUR_MONGODB_CONNECTION_STRING, etc.) with actual values.

4. Initialize Prisma
Set up your database schema:
```shell
npx prisma db push
```
5. Run the application
Start the development server:
```shell
npm run dev
````



## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
