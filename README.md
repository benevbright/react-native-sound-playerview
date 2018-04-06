# react-native-sound-playerview
audio player view using with [react-native-sound](https://github.com/zmxv/react-native-sound) and `react-navigation`

<img src="https://github.com/benevbright/react-native-sound-playerview/blob/master/docs/demo.gif?raw=true">


## Getting started

`$ npm install react-native-sound-playerview`

### Register Screen with `react-navigation`

```
import PlayerScreen from 'react-native-sound-playerview'

...

const Navigation = StackNavigator({
    ...
    player:{screen:PlayerScreen},
    ...
})

...
```

### Navigate to 'react-native-sound-playerview'
```
this.props.navigation.navigate('player', {title:__TITLE__, filepath:__AUDIO_FILEPATH__});
```