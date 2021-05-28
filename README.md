This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

This is repository for discussion about [theme-ui#1781][1]

Install the dependencies:

```
npm i
```

First, run the development server:

```bash
npm run dev
```

Issue:

When we want to style the headlessui components using `sx` props, it start giving the typescript error as below:

> Expression produces a union type that is too complex to represent.ts(2590)

If you remove `/** @jsxImportSource theme-ui */` and `sx` props, it does not complain about above error.


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

[1]: https://github.com/system-ui/theme-ui/discussions/1781
