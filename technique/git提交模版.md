# git提交模版

```
# head: <type>(<scope>): <subject>
# - type: feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert
# - scope: can be empty (eg. if the change is a global or difficult to assign to a single component), e.g: route, component, utils, build...
# - subject: start with verb (such as 'change'), 50-character line
#
# body: 72-character wrapped. Multiple lines separated by “-”, This should answer:
# * Why was this change necessary?
# * How does it address the problem?
# * Are there any side effects?
#
# footer: 
# - Include a link to the ticket, if any.
# - BREAKING CHANGE
#
# e.g:
# <type>(<scope>): <subject>
# <BLANK LINE>
# <body>
# <BLANK LINE>
# <footer>
# 
# types:
#
# feat:     A new feature 
# fix:      A bug fix 
# docs:     Documentation only changes 
# style:    Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc) 
# refactor: A code change that neither fixes a bug nor adds a feature 
# perf:     A code change that improves performance 
# test:     Adding missing tests or correcting existing tests
# build:    Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm) 
# ci:       Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) 
# chore:    Other changes that don't modify src or test files 
# revert:   Reverts a previous commit
```

