# liferay-npm-bundler-preset-reactjs
liferay npm bundler preset reactjs


# Install
```shell
npm install --save-dev liferay-npm-bundler-preset-reactjs
```

# Usage
Add the following to your .npmbundlerrc file:

```shell
{
    "preset": "liferay-npm-bundler-preset-react"
}
```

# Technical Details
This preset includes the following Babel presets:
```shell
babel-preset-liferay-standard
And the following Liferay NPM Bundler plugins:

liferay-npm-bundler-plugin-replace-browser-modules
```
