# multikult.ro

Static copy of the Multikult site, a project about the ethnic groups of the Banat region.

The original site was a KeystoneJS 4 app from 2017. Its database was empty, so the pages were
rendered once to plain HTML in October 2026 and the app was retired.

Hosted on Cloudflare Pages at https://www.multikult.ro. To deploy:

```
wrangler pages deploy . --project-name=multikult --branch=main
```

The contact form on `contact.html` has no backend and does not send anything.
