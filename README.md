<div align="center">
  <a href="https://superchargejs.com">
    <img width="471" style="max-width:100%;" src="https://superchargejs.com/images/supercharge-text.svg" />
  </a>
  <br/>
  <br/>
  <p>
    <h3>Issue Labels</h3>
  </p>
  <p>
    Issue labels for the Supercharge GitHub organization
  </p>
  <br/>
  <p>
    <em>Follow <a href="http://twitter.com/marcuspoehls">@marcuspoehls</a> and <a href="http://twitter.com/superchargejs">@superchargejs</a> for updates!</em>
  </p>
</div>

---

## Usage
Creating issue labels in a repository requires one of the many CLIs out there. We’ve used [git-labels-cli](https://github.com/bukinoshita/git-labels-cli) to import the `labels.json` file and create the issue labels on a given repo.

At first, install the `git-labels-cli` on your machine:

```
npm i -g git-labels-cli
```

Next, authenticate with GitHub by creating an authentication token:

```
git-labels --auth
```

Then, create the labels on a repo:

```
git-labels superchargejs/issue-labels
```

That’s it.

## License
MIT © [Supercharge](https://superchargejs.com)

---

> [superchargejs.com](https://superchargejs.com) &nbsp;&middot;&nbsp;
> GitHub [@superchargejs](https://github.com/superchargejs/) &nbsp;&middot;&nbsp;
> Twitter [@superchargejs](https://twitter.com/superchargejs)
