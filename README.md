# testWeb
my first website.
### How to run it
its is all contained in a docker container running ubeunt. it was made using vs code. just download it and reopen it in a container.

### adding new projects with their own git history
```sh
git subtree add --prefix=apps/test-web https://github.com/valiantlynx/test-web.git main --squash
git subtree pull --prefix=apps/test-web https://github.com/valiantlynx/test-web.git main --squash
git subtree push --prefix=apps/test-web https://github.com/valiantlynx/test-web.git main

```
https://valiantlynx.github.io/testWeb/
