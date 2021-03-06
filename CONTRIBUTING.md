# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](CODE-OF-CONDUCT.md). By participating in this project you agree to abide by its terms.

---

Ensure your pull request adheres to the following guidelines:

- Make an individual pull request for each suggestion.
- Use the following format: `- [package](link).`
- A description is not required, but encouraged when necessary.
- Additions should be added to the bottom of the relevant category. Maintainers will sort this based on relevance. We do not sort alphabetically to give emphasis that some resources are more important.
- Link to the GitHub repo if the project is on GitHub.
- Keep descriptions short and simple, but descriptive.
- Start the description with a capital and end with a full stop/period.
- Don't start the description with `A` or `An`.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- The pull request should have a useful title and include a link to the package and why it should be included.
- New categories or improvements to the existing categorization are welcome, but should be done in a separate pull request.
- To generate new table of contents, run the command `npm run toc`. Please refer to Installation section if the command does not work. You need to do this if you added a new subcategory.

### Installing Dependencies

You need the latest version of `node.js` and `npm`.

Install the dependencies locally:

```
npm i
```

You can run the command for creating Table of Contents without globally installing anything:

```
./utils/auto-toc.js
```

### Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult. If the maintainers notice anything that we'd like changed, we'll ask you to edit your PR before we merge it. If you're not sure how to do that, [here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md) on the different ways you can update your PR so that we can merge it.
