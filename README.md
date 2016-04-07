# productivity-tools
Set of personal scripts to improve productivity.

## Scripts descriptions

### JavaScript project

- `js/bump-version.py` changes the project version (support bower.json, packages.json and config.xml with the cordova option)
- `js/make-release.sh` use `bump-version.py` to create a new release according to gitflow recommendations and push that on `develop` and `master` branches

#### Ionic project

- `js/ionic/build-release.sh` builds an Android/iOS production-ready release (Note: **iOS part is still under development**)
