# Cannot output to /static

#### Why This Error Occurred

Either you set `distDir` to `static` in your `next.config.js` or during `next export` you tried to export to the `static` directory.

This is not allowed due to `static` being a special folder in Next.js used to serve static assets.

#### Possible Ways to Fix It

Use a different `distDir` or export to a different folder.

### Useful Links

- [Static file serving docs](https://nextjs.org/docs/basic-features/static-file-serving)
