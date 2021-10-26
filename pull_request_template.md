## Change description


> Description here

## Type of change
- [ ] Bug fix (fixes an issue)
- [ ] New feature (adds functionality)
- [ ] Chore (maintenance, clean up, etc)
- [ ] Documentation (README files, pom descriptions, etc)
- [ ] Style (formatting, whitespace, indentation, etc)
- [ ] Refactor (exclusively no functional change)
- [ ] Performance (exclusively, no functional change)
- [ ] Tests (No change to working codebase, only testing around it)

## Related issues/PRs and references

> Fix [#1]()
> Commit hash
> External system ID

## Checklists

### Development

- [ ] branchout mvn cv passes locally
- [ ] Major version bumped if breaking change
- [ ] Lint rules pass locally
- [ ] Application changes have been tested thoroughly
- [ ] Automated tests covering modified code pass

### Code best practices

- [ ] Global exception handling considered
- [ ] Log messages are relevant

### Security

- [ ] Security impact of change has been considered
- [ ] Code follows company security practices and guidelines

### Standards
- [ ] Commit comments are appropriate?
- [ ] Change notes included?

### Pre code review (for PR creator)

- [ ] Pull request has a descriptive title and context useful to a reviewer. Screenshots or screencasts are attached as necessary
- [ ] "Ready for review" label attached and reviewers assigned
- [ ] Github issue is referenced in the Pull Request or commit
- [ ] Commits are atomic and self contained
- [ ] Branch is complete and overall change functionally usable
- [ ] Committer and author name and email are correct/appropriate, not git defaults
- [ ] Branch contains no breaking changes or major version is bumped. (TODO link) Or did something break that you need to isolate? (TODO link)
- [ ] This change cannot be accomplished by overriding an existing client-side configuration variable
- [ ] This change is not client-specific and benefits Practiv long term

## I promise not to...

- [ ] Force push after review is done - instead add new commits with comments prefixed with "SQUASH" or "FIXUP" that can be `git rebase -i`'d later.
- [ ] Resolve conversations on behalf of the person who raised them - that's for them to do after you satisfy them or fix the issue in a new commit.

## PR Template Contributions

Contribute via PR here: https://github.com/practiv/.github
