## dhivehi.ai website

This repository contains contents for our [Website](htts://dhivehi.ai)

## Requirements

The website runs on Hugo, using [Doks](https://github.com/h-enk/doks).

Doks uses npm to centralize dependency management, making it [easy to update](https://getdoks.org/docs/help/how-to-update/) resources, build tooling, plugins, and build scripts:

- Download and install [Node.js](https://nodejs.org/) (it includes npm) for your platform.

## Contributing

* Create a fork of this repo
* Refer below and to [Doks documentation](https://getdoks.org/tutorial/introduction/) on making changes
* Ensure your changes run locally `npm run start`
* Make sure there are no linting errors `npm test`
* Create a pull request

### Creating a profile

Create a new page under "content/contributors" for yourself,
with a brief introduction and contact information as you wish.

### Creating a blog post

* First run
`npm run create blog/post-title-short/index.md`

* Edit your entry
* Ensure everything looks good locally
* Set draft = false once satisfied
* create a pull request

If you are updating the contributors tag in your post,
ensure you have a profile created as above.

### Creating a news item

Same as creating a blog post except run:
`npm run create news/post-title-short/index.md`

## Documentation

- [Hugo](https://gohugo.io/documentation/)
- [Doks](https://getdoks.org/)
