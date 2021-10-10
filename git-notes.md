# 📓 Git Notes

## 💻 Useful Commands
- `git status --ignored` will show you what is being ignored.
- `git commit --amend -m "an updated commit message"` to update your latest commit message if you made a typo.

## ✅ Commits
- [Gitmoji](https://gitmoji.dev/): An emoji guide for git commits. They're fun and can help you make better commits. Also see my [customized git commit emoji cheatsheet](git-commit-emoji.md).
- [Angular's configuration of commitlint](https://github.com/conventional-changelog/commitlint/tree/master/@commitlint/config-conventional#type-enum): Shows examples of categories of conventional git commit messages to help you make more sensible commits.
- [Karma commit style](https://karma-runner.github.io/0.10/dev/git-commit-msg.html): Shows examples of conventional commits.

To help make great commits, you can stage chunks of code -- you don't have to stage an entire file at once!<sup>[3](#references)</sup> in VS Code there's a way to visually select chunks to stage, as shown in the image below. You can also right click on the section of code you want to stage and an open will appear in the context menu for staging/un-staging the selected range.

![Image showing how to use interactive staging mode through VS Code interface](images/git/2021-08-24-19-03-02.png)

From the command line, you can do this with the `git add --patch` and `git add --interactive` for interactive modes.<sup>[4](#references)</sup>

## 🛠️ Tools
- [commitlint](https://github.com/conventional-changelog/commitlint): Linting for your commits.
- [github/gitignore](https://github.com/github/gitignore): A collection of useful `.gitignore` templates.

## 📙 Resources
- [Git Better](https://gitbetter.substack.com/): A newsletter about git tips.

## 📚 References
- [1]: [Comparing Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows)
- [2]: [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [3]: [How can I commit some changes to a file, but not others, in VSCode?](https://stackoverflow.com/questions/34730585/how-can-i-commit-some-changes-to-a-file-but-not-others-in-vscode)
- [4]: [git add --patch and --interactive](https://nuclearsquid.com/writings/git-add/)
- [5]: [How to Use a .gitignore File](https://www.pluralsight.com/guides/how-to-use-gitignore-file)
