# Guidelines for reviewing pull requests:
- Don't just approve blindly. Be honest with the PR author and strict with what you let into our codebase.
- Only approve PRs if you actually understand the purpose of the each code change, otherwise leave comments and ask the author. There are times the author will be sloppy hoping that reviewers will catch mistakes, and similarly reviewers wrongly trust the author for having been diligent.
- Only approve PRs if corresponding documentation (such as docstrings, parameter annotations, and external docs like READMEs and PMRA word documents) are also updated. We don't want to burden developers with too much documentation, but explaining large scale code changes, keeping docstrings and parameter annotations up to date is really important.
- Only approve PRs if all tests pass (unless there is some reasonable exception).
- Encourage authors to request PR reviews from a variety of team members. We don't want team members asking the same person for PR reviews every time (unless no one else has sufficient context for that codebase to review the PR). Ideally we want as many eyes on all parts of the code while still moving quickly.
