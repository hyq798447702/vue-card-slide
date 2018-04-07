# vue-card-slide

> A vue plugin for Carousel Card Slide

## Build Setup
```JS
npm install vue-card-slide --save
```

## Use 
```JS
// ES6 import
import cardSlide from 'vue-card-slide'
// require import
var cardSlide = require('CardSlide')

Vue.use(cardSlide)

// use in component
<vue-card-slide></vue-card-slide>
```

## config
```JS
<vue-card-slide @success='sucEvent' @error='errEvent'></vue-card-slide>
```

### event

| name | Description   |
| :--------:   | -----  |
|    success    |  leftSwipe
|    error    |  rightSwipe
