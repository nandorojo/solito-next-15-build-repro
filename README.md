Building with Next.js 15 is throwing.

```sh
yarn
yarn next build
```

You should see this error:

```sh
✓ Linting
 ✓ Collecting page data
Error occurred prerendering page "/". Read more: https://nextjs.org/docs/messages/prerender-error
TypeError: g(...).__CLIENT_INTERNALS_DO_NOT_USE_OR_WARN_USERS_THEY_CANNOT_UPGRADE?.A?.getOwner is not a function
```

Dev mode works with and without `--turbopack`.
