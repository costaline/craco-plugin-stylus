# Craco plugin stylus

-----

## Installation

1. Install [craco](https://github.com/gsoft-inc/craco/blob/master/packages/craco/README.md#installation)

2. Install stylus

	 ```sh
	 npm i stylus
	 ```

4. Install plugin:

   ```sh
   npm i -D @costaline/craco-plugin-stylus
   ```

5. Edit `craco.config.js`:

   ```js
   module.exports = {
     plugins: [
       {
         plugin: require("@costaline/craco-plugin-stylus"),
         options: {
           // stylus-loader options (see https://webpack.js.org/loaders/stylus-loader/#options)
         }
       }
     ]
   };
   ```
