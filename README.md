# ICU MessageFormat Helper

The ICU MessageFormat Helper is a powerful Chrome extension designed to assist linguists, translators, and developers in creating accurate and valid ICU MessageFormat strings. This tool is particularly useful for those working with complex ICU structures, including plurals, selects, gender, and other advanced message formatting rules.

## Installation
>Make sure you have Node.js version **above 16.17.0** and **below 20.x** installed.

Clone repo

```
git clone https://github.com/kitty885/message_format
```
Go to the `message_format` directory and run

```
npm install
```
Now build the extension using
```
npm run build
```
You will see a `build` folder generated inside `[PROJECT_HOME]`

To avoid running `npm build` after updating any file, you can run

```
npm run watch
```

which listens to any local file changes, and rebuilds automatically.

## Adding Message_Format extension to Chrome

In the Chrome browser, go to chrome://extensions page and switch on developer mode. This enables the ability to locally install a Chrome extension.

<img src="https://cdn-images-1.medium.com/max/1600/1*OaygCwLSwLakyTqCADbmDw.png" />

Now click on the `LOAD UNPACKED` and browse to `[PROJECT_HOME]\build`, This will install the React app as a Chrome extension.
<img src="https://drive.google.com/file/d/1I_9LXGAeNXkmJu9YNQ0qP0W1Qs8At6Gg/view?usp=drive_link" />

When you go to any website and click on the extension icon, the injected page will toggle.

<img src="https://cdn-images-1.medium.com/max/1600/1*bXJYfvrcHDWKwUZCrPI-8w.png" />

## Using SASS

Boilerplate contains [sass-loader](https://github.com/webpack-contrib/sass-loader), so you can use SASS instead of pure CSS in your project. To do so:
1. Rename ```src/App.css``` file to ```src/App.scss``` 
2. Change import line in ```src/app.js``` from 
 ```import './App.css';```  to ```import './App.scss';```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/satendra02/message_format/. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The repo is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).


## Available Scripts

In the project directory, you can run:

### `npm run build`
bundle the extension.

### `npm run watch`
bundle the extension with interactive watch mode.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
