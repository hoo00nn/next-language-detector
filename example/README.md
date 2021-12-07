# Static internationalized (i18n) next.js website with the help of [next-i18next](https://github.com/isaachinman/next-i18next) and [next-language-detector](https://github.com/adrai/next-language-detector)

## What is this?

This is a simple example of how to use [next-i18next](https://github.com/isaachinman/next-i18next) with [NextJs](https://github.com/zeit/next.js) for a complete static website and optional use of [locize](https://locize.com) to get translations up and running quickly and easily.

## For more info...

You may have arrived here from the [NextJs](https://github.com/zeit/next.js) repository, from [next-i18next](https://github.com/isaachinman/next-i18next) repository or the [react-i18next](https://github.com/i18next/react-i18next/) repository. Either way, for more documentation on:

- **next-i18next**, please visit the [main README](https://github.com/isaachinman/next-i18next)
- **NextJs**, please visit the [website](https://nextjs.org/)
- **locize** in combination with NextJs, please visit the [main README](https://github.com/locize/next-i18next-locize)


## optional locize usage (not mandatory)

Before "deploying" your app, you can run the [downloadLocales script](https://github.com/adrai/next-language-detector/blob/main/example/package.json#L15) (or similar), which will use the [cli](https://github.com/locize/locize-cli) to download the translations from locize into the appropriate folder next-i18next is looking in to (i.e. ./public/locales).