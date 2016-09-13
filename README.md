# React Countdown Clock

A HTML 5 canvas countdown clock as a React component.

## Demo

[pughpugh.github.io/react-countdown-clock](http://pughpugh.github.io/react-countdown-clock)

## Installation

```
npm install react-countdown-clock-fork
```

## Usage

```javascript
<ReactCountdownClock
  seconds={60}
  color="#000"
  alpha={0.9}
  size={300}
  onComplete={myCallback}
/>
```

## Props

| prop              | type           | default | description                                              |
|-------------------|----------------|---------|----------------------------------------------------------|
| seconds           | integer        | 60      | Seconds to countdown                                     |
| color             | string         | #000    | Colour of counter                                        |
| alpha             | float          | 1.0     | Alpha transparency of counter                            |
| size              | integer        | 300     | Width & height of canvas element                         |
| weight            | integer        |         | Weight of circle, in pixels                              |
| fontSize          | integer/string | auto    | px size of font. `auto` for dynamic sizing.              |
| font              | string         | Arial   | Font of counter                                          |
| timeFormat        | string         | seconds | Counter style; `seconds` or `hms`                        | 
| showMilliseconds  | boolean        | true    | Show milliseconds for last 10 seconds                    |
| onComplete        | func           |         | Callback when time completes                             |
| restartOnNewProps | boolean        | true    | Restart timer when new props are passed to the component |

##Note

This is a temporary fork. Please refer to the [original repo](https://github.com/pughpugh/react-countdown-clock).
