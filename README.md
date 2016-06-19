# eslint-config

For Ember projects, look at the instructions found in the [.eslint.js.ember](.eslint.js.ember) file.

For any projects that use Git, copy and paste [pre-commit](pre-commit) to `.git/hooks/pre-commit`. Git will execute this script whenever you try to commit, and the script will block the commit from going through if there are any ESLint errors.
