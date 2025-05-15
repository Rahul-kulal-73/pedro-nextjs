# Creating a New Project
```bash
npx create-next-app .
```
You will be prompted with the following options:

- √ Would you like to use TypeScript? ... No / Yes ✅
- √ Would you like to use ESLint? ... No / Yes ✅
- √ Would you like to use Tailwind CSS? ... No / Yes ✅
- √ Would you like your code inside a src/ directory? ... No ✅ / Yes
- √ Would you like to use the App Router? (recommended) ... No / Yes ✅
- √ Would you like to use Turbopack for next dev? ... No / Yes ✅
- √ Would you like to customize the import alias (@/* by default)? ... No ✅ / Yes
Creating Routes & Navigation
To create a route, simply create a folder inside the app directory. Example: Create a folder named about, and inside it, create a page.tsx file. When a user accesses localhost:3000/about, the content of page.tsx will be displayed.

This content is rendered through the {children} prop in layout.tsx.

Use the <Link> tag for navigation (similar to the standard <a> tag).
