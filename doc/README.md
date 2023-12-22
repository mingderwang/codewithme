# Learning by Examples

:tada:Create an empty astro project

```
Script started on Fri Dec 22 09:43:24 2023
default -> v18.17.1
Now using node v18.17.1 (npm v9.6.7)
👉npx bun create astro@latest -- --template minimal

 astro   Launch sequence initiated.

   dir   Where should we create your new project?
         ./create-an-empty-astro
      ◼  tmpl
         Using minimal as project template
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
 cd ./create-an-empty-astro
 Run npm run dev to start the dev server. CTRL+C to stop.
 Add frameworks like react or tailwind using astro add.

 Stuck? Join us at https://astro.build/chat

╭──❄️─╮  Houston:
│ ○ ○ ○
╰─────╯

╭──❄️─╮  Houston:
│ ◠ ◡ ◠  Good luck out there, astronaut! 🚀
╰─────╯
👉 cd ./create-an-empty-astro
👉bun i
bun install v1.0.18 (36c316a2)
[49.04ms] migrated lockfile from package-lock.json

 58 packages installed [519.00ms]
👉bun test
bun test v1.0.18 (36c316a2)
The following filters did not match any test files:

13 files were searched [205.00ms]

note: Tests need ".test", "_test_", ".spec" or "_spec_" in the filename (ex: "MyApp.test.ts")

Learn more about the test runner: https://bun.sh/docs/cli/test
👉bun dev
$ astro dev

 astro  v4.0.7 ready in 344 ms

┃ Local    http://localhost:4321/
┃ Network  use --host to expose

09:46:20 watching for file changes...
^C
👉bun start --open
$ astro dev --open

 astro  v4.0.7 ready in 303 ms

┃ Local    http://localhost:4321/
┃ Network  use --host to expose

09:46:36 watching for file changes...
09:46:39 [200] / 33ms
09:46:39 [200] / 34ms
^C
👉exit

Script done on Fri Dec 22 09:46:49 2023
```
