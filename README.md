Yeoman generators generate assets of your react-native application.

_As of now, the way those generators are configured is heavily opinionated and based on our own company needs._

## Features

* [Icons and Splashscreen generation](generators/assets/README.md) -- `yo rn-toolbox:assets [--icon | --splash] <path>`

## Requirements
* [ ] You need `node > 6` installed
* [ ] Ruby > `2.2.3`* [ ] Ruby > `2.2.3`
* [ ] Bundler installed (`gem install bundler`)
* [ ] Yeoman installed (`npm i -g yo`)
* [ ] Yarn installed (`brew install yarn`)

## Usage

Install the main `yeoman` generator:

```
npm install -g yo generator-rn-toolbox
```

## Contributing

See [our contributing guidelines](https://bamlab.github.io/open-source/#contributing)

### Local development

To run the generator with your local version:

```shell
git clone https://github.com/bamlab/generator-rn-toolbox.git
cd generator-rn-toolbox
npm link
```

When you're done, you can run `npm unlink` to stop using your local version.
