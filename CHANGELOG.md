# v0.4.0 (Wed Jul 20 2022)

### Release Notes

#### Scope naming for kt_jvm intermediate targets ([#3](https://github.com/player-ui/rules_player/pull/3))

If the target name is the same as the local package name, the generated targets will omit the names. 

### Regular scope naming strategy:
```python

#### broader maven publishing support ([#9](https://github.com/player-ui/rules_player/pull/9))

- Maven Central compliant POM (`developers` tag)
- Coordinate `deploy_maven` targets under a single staging repository
- Allow for GPG passphrase

---

#### 🚀 Enhancement

- Scope naming for kt_jvm intermediate targets [#3](https://github.com/player-ui/rules_player/pull/3) ([@sugarmanz](https://github.com/sugarmanz))
- broader maven publishing support [#9](https://github.com/player-ui/rules_player/pull/9) ([@sugarmanz](https://github.com/sugarmanz))

#### Authors: 1

- Jeremiah Zucker ([@sugarmanz](https://github.com/sugarmanz))

---

# v0.3.0 (Wed Jul 20 2022)

#### 🚀 Enhancement

- Add stamp substitution support for nextjs docs [#10](https://github.com/player-ui/rules_player/pull/10) ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.2.1 (Sun Jul 17 2022)

#### 🐛 Bug Fix

- Fix package name resolution for create_package_json [#8](https://github.com/player-ui/rules_player/pull/8) ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.2.0 (Fri Jul 15 2022)

### Release Notes

#### Add better support for publishing npm packages ([#6](https://github.com/player-ui/rules_player/pull/6))

* Adds support for `registry` in the `js_pipeline`
* Adds `private` flag to omit publishing a package to `npm`
* Fixes version substitutions

---

#### 🚀 Enhancement

- Add better support for publishing npm packages [#6](https://github.com/player-ui/rules_player/pull/6) ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.1.0 (Wed Jul 13 2022)

### Release Notes

#### Add rule for publishing to org-level github-pages repo ([#5](https://github.com/player-ui/rules_player/pull/5))

Adds a new rule for handling github-pages deployments specific to an organization. 
Releases are organized by major version number, with aliases for the latest release and canary versions.

---

#### 🚀 Enhancement

- Add rule for publishing to org-level github-pages repo [#5](https://github.com/player-ui/rules_player/pull/5) ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.0.3 (Fri Jun 24 2022)

#### ⚠️ Pushed to `main`

- update kotlin rules sha checksum ([@sugarmanz](https://github.com/sugarmanz))

#### Authors: 1

- Jeremiah Zucker ([@sugarmanz](https://github.com/sugarmanz))

---

# v0.0.2 (Tue Jun 21 2022)

### Release Notes

#### Change rule name to just rules_player ([#1](https://github.com/player-ui/rules_player/pull/1))

Changes documentation and examples to use `@rules_player` as the workspace name

---

#### 🐛 Bug Fix

- Handle duplicate data refs in build + test rules [#2](https://github.com/player-ui/rules_player/pull/2) ([@adierkens](https://github.com/adierkens))
- Change rule name to just rules_player [#1](https://github.com/player-ui/rules_player/pull/1) ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))

---

# v0.0.1 (Thu Jun 09 2022)

#### ⚠️ Pushed to `main`

- Add auto name ([@adierkens](https://github.com/adierkens))
- Update deps ([@adierkens](https://github.com/adierkens))
- Fix circle config ([@adierkens](https://github.com/adierkens))
- fix executor ([@adierkens](https://github.com/adierkens))
- Add circle and auto ([@adierkens](https://github.com/adierkens))
- fix paths ([@adierkens](https://github.com/adierkens))
- Add player rules ([@adierkens](https://github.com/adierkens))

#### Authors: 1

- Adam Dierkens ([@adierkens](https://github.com/adierkens))
