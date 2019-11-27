# Jekyll Blog with Minima Theme

## Deployed on Netlify
https://distracted-spence-debcfb.netlify.com

### Local Installation

1. `git clone https://github.com/katrose/minima-final`
2. `script/bootstrap` to install dependencies
3. `script/server` to build site and make it available on local server
4. Go to http://localhost:4000 to see website

## Notes on Deliverables

### Posts
`jekyll-paginate` can only be used on index.html, so for this assignment, the blog posts will be on the home page.

(If using [`jekyll-paginate-v2`](https://github.com/sverrirs/jekyll-paginate-v2) you can specify the target page, but I used v1)

### Contact Form

Location: _layouts/contact.html

[Formspree](https://formspree.io/) provides an endpoint to the contact form so that users can submit a message or comment which will be directed to my email inbox.
