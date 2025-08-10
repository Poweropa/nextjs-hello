# nextjs-hello

## Startup project

```
mkdir nextjs-hello
cd nextjs-hello
```

## Install Nextjs

```
npx create-next-app@latest nextjs
```

**... alternative use my code**

```
git clone https://github.com/Poweropa/nextjs-hello.git .
```

**then press:**

- y (Yes - install packages)
- Enter (Yes - TypeScript)
- Enter (Yes - ESLint)
- Enter (Yes - Tailwind CSS)
- Enter ( No - src/)
- Enter (Yes - App Router)
- Enter (Yes - Turbopack)
- Enter ( No - import alias)

## Start Server

```
cd nextjs
npm run dev
```

## Run Application

Open your browser: http://localhost:3000

## Start Developing with live update

1. Open your IDE (e.g. Visual Studio Code)
2. Make changes (e. g. /app/page.tsx) and save (Ctrl + s)
   _Example /app/page.tsx file:_

   ```
   import Image from "next/image";

   export default function Home() {
     return <>Hello World</>;
   }

   ```

3. Your browser should reload automatically
