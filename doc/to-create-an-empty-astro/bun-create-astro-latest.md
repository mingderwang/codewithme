# bun create astro@latest

```
👉npx bun create astro@latest -- --template minimal
```

or

```
👉npx bun create astro@latest
```

:tada: More option or templates can see in the Bun official docs -> [here](https://bun.sh/docs/cli/bun-create)

```
Script started on Fri Dec 22 11:45:18 2023
default -> v18.17.1
Now using node v18.17.1 (npm v9.6.7)
👉 npx bun create astro@latest

 astro   Launch sequence initiated.

   dir   Where should we create your new project?
         ./nuclear-neutron

  tmpl   How would you like to start your new project?
         Include sample files
 ██████  Template copying...

  deps   Install dependencies?
         Yes
 ██████  Installing dependencies with npm...

    ts   Do you plan to write TypeScript?
         Yes

   use   How strict should TypeScript be?
         Strict
 ██████  TypeScript customizing...

   git   Initialize a new git repository?
         Yes
 ██████  Git initializing...

  next   Liftoff confirmed. Explore your project!

 Enter your project directory using
 cd ./nuclear-neutron
 Run npm run dev to start the dev server. CTRL+C to stop.
 Add frameworks like react or tailwind using astro add.

 Stuck? Join us at https://astro.build/chat

╭──🎁─╮  Houston:
│ ◠ ◡ ◠  Good luck out there, astronaut! 🚀
╰─────╯
👉 cd ./nuclear-neutron
👉 tree -I node_modules -I dist
.
├── README.md
├── astro.config.mjs
├── package-lock.json
├── package.json
├── public
│   └── favicon.svg
├── src
│   ├── components
│   │   └── Card.astro
│   ├── env.d.ts
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── tsconfig.json

6 directories, 10 files
👉 exit

Script done on Fri Dec 22 11:48:09 2023
```
