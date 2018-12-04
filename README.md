# npmias

> NPM commands and their aliases

I want to provide a quick reference resource guide to [NPM](https://docs.npmjs.com/cli-documentation/) aliases. This outline-style README provides an overview of NPM commands that have aliases, don't have aliases, and links to the official NPM documentation for all the other NPM commands that aren't deprecated.

## Aliases that are Shortcuts

### [**_install_**](https://docs.npmjs.com/cli/install.html)

```bash
npm install chalk
```

alias

```bash
npm i chalk
```

### [**_test_**](https://docs.npmjs.com/cli/test.html)

```bash
npm test
```

alias

```bash
npm t
```

or

```bash
npm tst
```

### [**_config_**](https://docs.npmjs.com/cli/config.html)

```bash
npm config edit
```

alias

```bash
npm c edit
```

### [**_install-ci-test_**](https://docs.npmjs.com/cli/install-ci-test.html)

```bash
npm install-ci-test
```

alias

```bash
npm cit
```

### [**_install-test_**](https://docs.npmjs.com/cli/install-test.html)

```bash
npm install-test
```

alias

```
npm it
```

### [**_rebuild_**](https://docs.npmjs.com/cli/rebuild.html)

```bash
npm rebuild
```

alias

```
npm rb
```

### [**_link_**](https://docs.npmjs.com/cli/link.html)

```bash
cd ~/projects/node-redis    # go into the package directory
npm link                    # creates global link
cd ~/projects/node-bloggy   # go into some other package directory.
npm link redis              # link-install the package
```

alias

```bash
npm ln ...
```

### [**_run-script_**](https://docs.npmjs.com/cli/run-script.html) \*

```bash
npm run-script lint
```

alias

```bash
npm run lint
```

### [**_search_**](https://docs.npmjs.com/cli/search.html)

```bash
npm search ...
```

alias

```bash
npm s ...
```

or

```bash
npm se ...
```

or

```bash
npm find ...
```

### [**_uninstall_**](https://docs.npmjs.com/cli/uninstall.html)

```bash
npm uninstall chalk
```

alias

```bash
npm rm chalk
```

or

```bash
npm r chalk
```

or

```bash
npm remove chalk
```

or

```bash
npm un chalk
```

or

```bash
npm unlink chalk
```

### [**_update_**](https://docs.npmjs.com/cli/update.html)

```bash
npm update
```

alias

```bash
npm up
```

or

```bash
npm upgrade
```

### [**_version_**](https://docs.npmjs.com/cli/version.html)

```bash
npm version
```

alias

```
npm -v
```

or

```
npm --version
```

### [**_view_**](https://docs.npmjs.com/cli/view.html)

```bash
npm view
```

alias

```bash
npm v
```

or

```bash
npm info
```

or

```bash
npm show
```

## Aliases that aren't Shortcuts

### [**_adduser_**](https://docs.npmjs.com/cli/adduser.html)

```bash
npm adduser --registry=http://myregistry.example.com --scope=@myco
```

alias

```bash
npm add-user ...
```

or

```bash
npm login ...
```

### [**_bugs_**](https://docs.npmjs.com/cli/bugs.html)

```bash
npm bugs chalk
```

alias

```bash
npm issues chalk
```

### [**_cache clean_**](https://docs.npmjs.com/cli/cache.html) \*

```bash
npm cache clean
```

alias

```bash
npm cache rm
```

or

```bash
npm cache clear
```

### [**_npm dedupe_**](https://docs.npmjs.com/cli/dedupe.html)

```bash
npm dedupe
```

alias

```bash
npm ddp
```

or

```
npm find-dupes
```

### [**_npm dist-tag_**](https://docs.npmjs.com/cli/dist-tag.html)

```bash
npm dist-tag add chalk@1.0.0 sometag
```

alias

```bash
npm dist-tags
```

### [**_ls_**](https://docs.npmjs.com/cli/ls.html)

```bash
npm ls
```

alias

```bash
npm list
```

or

```bash
npm la
```

or

```bash
npm ll
```

### [**_owner_**](https://docs.npmjs.com/cli/owner.html)

```bash
npm owner add bobdole @angular/cli
```

```bash
npm author ...
```

### [**_docs_**](https://docs.npmjs.com/cli/docs.html)

```bash
npm docs ...
```

```bash
npm home ...
```

## Commands with no Aliases

- [access](https://docs.npmjs.com/cli/access.html)
- [audit](https://docs.npmjs.com/cli/audit.html)
- [bin](https://docs.npmjs.com/cli/bin.html)
- [build](https://docs.npmjs.com/cli/build.html)
- [ci](https://docs.npmjs.com/cli/ci.html)
- [completion](https://docs.npmjs.com/cli/completion.html)
- [deprecate](https://docs.npmjs.com/cli/deprecate.html)
- [doctor](https://docs.npmjs.com/cli/doctor.html)
- [edit](https://docs.npmjs.com/cli/edit.html)
- [explore](https://docs.npmjs.com/cli/explore.html)
- [help-search](https://docs.npmjs.com/cli/help-search.html)
- [help](https://docs.npmjs.com/cli/help.html)
- [hook](https://docs.npmjs.com/cli/hook.html)
- [init](https://docs.npmjs.com/cli/init.html)
- [logout](https://docs.npmjs.com/cli/logout.html)
- [npm](https://docs.npmjs.com/cli/npm.html)
- [outdated](https://docs.npmjs.com/cli/outdated.html)
- [pack](https://docs.npmjs.com/cli/pack.html)
- [ping](https://docs.npmjs.com/cli/ping.html)
- [prefix](https://docs.npmjs.com/cli/prefix.html)
- [publish](https://docs.npmjs.com/cli/publish.html)
- [repo](https://docs.npmjs.com/cli/repo.html)
- [restart](https://docs.npmjs.com/cli/restart.html)
- [root](https://docs.npmjs.com/cli/root.html)
- [shrinkwrap](https://docs.npmjs.com/cli/shrinkwrap.html)
- [star](https://docs.npmjs.com/cli/star.html)
- [stars](https://docs.npmjs.com/cli/stars.html)
- [start](https://docs.npmjs.com/cli/start.html)
- [stop](https://docs.npmjs.com/cli/stop.html)
- [team](https://docs.npmjs.com/cli/team.html)
- [token](https://docs.npmjs.com/cli/token.html)
- [unpublish](https://docs.npmjs.com/cli/unpublish.html)
- [whoami](https://docs.npmjs.com/cli/whoami.html)

## Acknowledgments

npmias was inspired by [@styfle](https://twitter.com/styfle)!

## See Also

[`noffle/common-readme`](https://github.com/noffle/common-readme)

## License

[LICENSE](LICENSE)
