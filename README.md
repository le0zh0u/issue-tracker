This is a demo project for practicing Next.js, Prisma, Tailwind CSS.

Learning from Youtube video: https://www.youtube.com/watch?v=J9sfR6HN6BY

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Something to learn
 
### use `rafce`
Use `rafce` to create React page export module quickly.

### react-icons
Use icons from `react-icons `

### classnames
combine classname with conditions.

example:
``` tsx
className={classnames({'text-black-900':isCurrentPage, 'text-black-500':!isCurrentPage, 'hover:text-blue-800': true})}
```

In the code, text is a link in nav. If the text is matched current page path, it will display as `black-900`, othewise it will display as `black-500`. if pointer is hovering the text, it will display as `black-800`

### color transition
Use `className = 'transition-colors'`, can let color change smoothly.

### prisma

#### init prisma
`npx prisma init`

#### form prisma schema
`npx prisma format`

It will format file named `schema.prisma`.

#### migrate
`npx prisma migrate dev`

- create `migrations` folder
- generate migrate sql
- create table in DB

### Radix-UI
UI components base with Tailwind CSS

### Markdown Editor
`react-simplemde-editor`

### Form Validation

`react-hook-form`

`zod`

