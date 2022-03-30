# Farewell Owl!

This is the site for the final goodbye page that is now the OwlGaming homepage.

## Install

Ensure you have `hugo-extended` installed. For builds (other than serve) you should have the
following dependencies installed with at least Node v16
```shell
npm i -g postcss postcss-cli autoprefixer
```

Now start it up!

```shell
git submodule update --init --recursive
hugo serve
```

## Contributions

Contributions are welcome for fixing any typos or adding useful stats.

### Stories

We even would encourage you to add your own story about Owl to the blogs section. Feel
free to reach out to Chaos on [Discord](https://discord.gg/0pqjfCF59OHw3ccp) for how to do this. 

The short steps are:

```
# If there is no current index, add one
hugo new blog/_index.md

# Create your blog page
hugo new blog/YourUsername.md
```

Add your story to the `content/blog/YourUsername.md` file in [Markdown](https://www.markdownguide.org/) format and submit a PR.
