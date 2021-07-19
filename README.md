If you're looking to **build a website or a cross-platform mobile app** – we will be happy to help you! Send a note to clients@ui1.io and we will be in touch with you shortly.

![Chart Kit](https://i.imgur.com/Idp4WIX.jpg)

[📲See example app](https://github.com/indiespirit/react-native-chart-kit-example)

To try the examples in Expo, please change `main` to `./node_modules/expo/AppEntry.js` in `package.json` before starting things with `expo run`. You'll need to have `expo-cli` installed via `npm install -g expo-cli`.

# React Native Chart Kit Documentation

## Import components

This package is forked from https://github.com/indiespirit/react-native-chart-kit. I've added the pressable bar graph functionality.

1. `yarn add react-native-chart-kit-with-pressable-bar-graph`
   Just use this for the bar graph.

We'll have the onDataPointClick - which will give us the x - will be the starting point , y - will be the starting point , index and value of the bar graph.

So, we can use those values.

Then we can use the decorator, which can be React Component within the graph.

Here's a good article on how we can use both of these functions together -
https://levelup.gitconnected.com/adding-tooltip-to-react-native-charts-67606c5d3182

After that, do these steps - and use it for other charts.

1. `yarn add react-native-chart-kit`
2. `yarn add react-native-svg` install peer dependencies
3. Use with ES6 syntax to import components

## Contribute

See the [contribution guide](contributing.md) and join [the contributors](https://github.com/indiespirit/react-native-chart-kit/graphs/contributors)!
