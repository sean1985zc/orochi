Contributors Guidelines
=======================

Contributions to Orochi are welcome! Please adhere to the following
contribution guidelines though:

- Run the [test suite](https://github.com/dbrgn/orochi#testing) before
  committing and pushing your changes.
- Please follow the [coding
  guidelines](https://github.com/dbrgn/orochi#coding-guidelines).
- Use meaningful commit messages: First line of your commit message should be a
  very short summary (ideally 50 characters or less). After the first line of
  the commit message, add a blank line and then a more detailed explanation (when
  relevant).  [This](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
  is a nice blog post concerning git commit messages.
- Add yourself to the [AUTHORS file](https://github.com/dbrgn/orochi/blob/master/AUTHORS).

The following items make my life easier, but are optional:

- If you know how to use `git rebase`, please rebase/sqash your commits so that
  unnecessary noise in the commit history is avoided.
- If you have have previously filed a GitHub issue and want to contribute code
  that addresses that issue, I prefer it if you use
  [hub](https://github.com/github/hub) to convert your existing issue to a pull
  request. To do that, first push the changes to a separate branch in your fork
  and then issue the following command:

        hub pull-request -b dbrgn:master -i <issue-number> -h <your-github-username>:<your-branch-name>

  This is no strict requirement though, if you don't have hub installed or
  prefer to use the web interface, then feel free to post a traditional pull
  request.

Thanks for your contribution!
