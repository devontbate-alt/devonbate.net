# devonbate.net

The site at devonbate.com as Netlify serves it: static pages, fonts,
images and the Netlify config. Every file here is written by
tools/publish.mjs in the private source repository, on each push to its
main branch. An edit made here is overwritten by the next publish; the
words live in the source repository's content files, and the pages are
rendered from them.

Netlify deploys the main branch of this repository with no build command
and the publish directory set to the root.
