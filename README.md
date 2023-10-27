# My Reflection

The current date and time is of when the code is run on the server. Because by default all components in Next.js are React Server Components, incl. layout.js, page.js etc.

The benefits of this over client side rendering is it's faster (though not obvious in this case) and user won't have to stare at a blank screen when waiting for the JavaScript to be downloaded.

# Next 13 template

This is a _super minimal_ starter for Next 13's App Router.

Not intended for use in production. Purely used for educational reasons.

## Running a development server

First, install the dependencies:

```bash
$ npm install
```

Then, start a local development server:

```bash
$ npm run dev
```

**Note:** Unlike create-react-app, we need to run the `dev` command, not `start`. The `start` command is used to run a _production_ server; we'll learn more about that later in the course.

## Troubleshooting

- Please make sure you're using Node.js version 16.14 or higher. This is the minimum Node version required by Next.js.
  - You can find your current Node version by running `node -v` in a terminal. If the value is less than 16.14, you'll want to upgrade Node to the [current LTS (Long Term Support) version](https://nodejs.org/en).
