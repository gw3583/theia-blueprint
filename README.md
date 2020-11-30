<br/>
<div id="theia-logo" align="center">
    <br />
    <img src="https://raw.githubusercontent.com/eclipse-theia/theia/master/logo/theia-logo.svg?sanitize=true" alt="Theia Logo" width="300"/>
    <h3>Cloud & Desktop IDE Platform</h3>
</div>

<div id="badges" align="center">

Eclipse Theia is an extensible platform to develop full-fledged multi-language Cloud & Desktop IDE-like products with state-of-the-art web  technologies.

</div>

[![Installers](https://img.shields.io/badge/download-installers-blue.svg?style=flat-curved)](https://download.eclipse.org/theia/)

[Main Theia Repository](https://github.com/eclipse-theia/theia)

[Visit the Theia website](http://www.theia-ide.org) for more [documentation](http://www.theia-ide.org/doc).

## License

- [Eclipse Public License 2.0](LICENSE)
- [一 (Secondary) GNU General Public License, version 2 with the GNU Classpath Exception](LICENSE)

## Trademark
"Theia" is a trademark of the Eclipse Foundation
https://www.eclipse.org/theia

## Development

### Repository structure

- Root level configures mono-repo build with lerna
- `electron-app` contains app to package, packaging configuration, and E2E tests.
- `theia-example-updater` contains Theia extension to update the package app at runtime.

### Build

```sh
yarn
```

### Package the application

```sh
yarn package
```

The packaged application is located in `electron-app/dist`.

### Create a preview application (without packaging it)

```sh
yarn package:preview
```

The packaged application is located in `electron-app/dist`.

### Troubleshooting

- [_"Don't expect that you can build app for all platforms on one platform."_](https://www.electron.build/multi-platform-build)
