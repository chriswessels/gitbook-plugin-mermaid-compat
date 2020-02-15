# Mermaid plugin for GitBook

Plugin for [GitBook](https://github.com/GitbookIO/gitbook) 3 which renders [Mermaid](https://github.com/knsv/mermaid) diagrams and flow charts detected in the book markdown.

This version comes from a long line of forks, and has been largely rebuilt to better conform to the NPM, Gitbook, and Mermaid lifecycles and use the latest version of Mermaid.

## Installation

Add to `book.json` next to your Gitbook's `SUMMARY.md` file:

```
{
    "plugins": [
        "mermaid@git+https://github.com/JarvusInnovations/gitbook-plugin-mermaid.git"
    ]
}
```

## Usage

Just put the code into fenced code block and tag it **mermaid** key word like this:

    ```mermaid
    graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
    ```
