# Markdown Link Issue

I've encountered an issue when using links within a `markdown` file, specifically inside [blockquotes](https://www.markdownguide.org/basic-syntax/#blockquotes-1).

The issue occurs only on the main page of a branch when the URL is `/tree/<branch-name>` like [https://github.com/Nougatos/github-markdown-url-issue/tree/main](https://github.com/Nougatos/github-markdown-url-issue/tree/main).

The link works as intended when you are in the blob URL like [https://github.com/Nougatos/github-markdown-url-issue/blob/main/README.md](https://github.com/Nougatos/github-markdown-url-issue/blob/main/README.md).

## Go [here](https://github.com/Nougatos/github-markdown-url-issue/tree/main) and test these examples

This [link to imagination](IMAGINATION.md) works properly.

> However, this [link to imagination](IMAGINATION.md) does not work within a blockquote.

- This [link to imagination](IMAGINATION.md) works properly in a list.

> > Interestingly, this [link to imagination](IMAGINATION.md) also doesn't work within nested blockquotes.

## Note: This [link to imagination](IMAGINATION.md) works properly in a header
