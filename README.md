# React Native Svg Circular Progress

A circular progress chart using react-native-svg

![sample <>](https://github.com/stssoftware/react-native-svg-circular-progress/raw/master/Sample.png "Sample")

## Installation
````
npm install react-native-svg react-native-svg-circular-progress --save
react-native link
````

## Usage
````jsx
import {CircularProgress} from 'react-native-svg-circular-progress'

const App = () => {
  const percentage = 40
  return <View>
    <CircularProgress percentage={percentage}>
      <View>
        <Text>{percentage}%</Text>
      </View>
    </CircularProgress>
  </View>
}
````

## Props
 * percentage (default: 80)
 * blankColor (default: "#eaeaea")
 * donutColor (default: "#43cdcf")
 * fillColor (default: "white")
 * progressWidth (default: 35)
 * size (default: 100)
