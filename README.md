## Demo
https://jiayingy.github.io/vue-single-date-picker/

## Installation
*Plugin is currently only available via Github packages* 

Add the following line to your `package.json`,
```javascript
dependencies {
  "@jiayingy/vue-single-date-picker": "0.4.2"
}
```

Run `npm install`

## How to use

### Component

Import package
```javascript
import SingleDatePicker from '@jiayingy/vue-single-date-picker';

export default {
  components: {
    SingleDatePicker
  }
}
```

Create component in your template
```javascript
<SingleDatePicker />
```

### Styles
In your scss file,
```
@import '~@jiayingy/vue-single-date-picker/dist/vue-single-date-picker.css';
```

### Events 
|events|arguments|remarks|
|:--|:--|:--|
|@selectDate|```{ year: <Number>, month: <Number>, date: <Number> }```|E.g. 1 Jan 2020 <br> {year: 2020, month: 0, date: 1}| 
