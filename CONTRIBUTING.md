## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. **We heartily welcome any and all contributions that match our code style standards!**

That being said, this codebase isn't your typical open source project because it's not a library or package with a limited scope — it's an entire product.

### Ground Rules

**Contributions and discussion guidelines**

- All discussions agree to GitHub's [Community Guidelines](https://help.github.com/en/github/site-policy/github-community-guidelines) and [Acceptable Use Policies](https://help.github.com/en/github/site-policy/github-acceptable-use-policies). We expect discussions in issues and pull requests to stay positive, productive, and respectful.

**Reporting a bug or discussing a feature idea**

- If you found a technical bug or have ideas for features we should implement, open a new issue. Make sure to follow the issue template and you should be golden! ([click here to open a new issue](https://github.com/chingu-voyages/v39-toucans-team-01/issues/new/choose))

**Fixing a bug or implementing a new feature**

- If you find a bug and open a PR that fixes it we'll review it as soon as possible to ensure it matches our code style standards.
- If you want to implement a new feature, open an issue first to discuss what it'd look like and to ensure it fits in our roadmap and plans for the app (see [the roadmap](https://github.com/chingu-voyages/v39-toucans-team-01/issues) for planned and currently ongoing work).

## Prerequisites

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [NPM](http://npmjs.com)) installed.
```
node@v16.14.2 or higher
yarn@1.22.18 or higher
git@2.35.1 or higher
```

## Getting Started 🔧

From your command line, first clone v39-toucans-team-01:

```bash
# Clone this repository
$ git clone https://github.com/chingu-voyages/v39-toucans-team-01.git

# Go into the repository
$ cd v39-toucans-team-01
```

Then you can install the dependencies:

```bash
# Install dependencies
$ yarn

# Start development server
$ yarn start
```

# Branching

## PR/Commit naming convention
Follow the [keyword](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) with a "/" then the issue number, then and "_" then use kabob case for the rest of the branch name.

**Examples**: 
- feat/#3_add-readme
- perf/#40_fix-slow-component
- fix/#22_padding-error

1. Create your Feature Branch (`git checkout -b feature/#<issue_number>_amazing-feature`)
2. Commit your Changes (`git commit -m "feat: add some amazing feature"`)
3. Push to the Branch (`git push -u origin feature/#<issue_number>_amazing-feature`)
4. Open a Pull Request

## PR summary

### Resolves ##issue_number
{summary of changes}

### What was changed?
{ Resolves #issue_number }

### Why was this important?

{explain why you implemented this feature}
