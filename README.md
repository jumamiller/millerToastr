# @jumamiller/vue2-toastr([English Doc](/README.en.md))


**@jumamiller/vue2-toastr(https://github.com/)**

npm
```bash
npm install @jumamiller/vue2-toastr --save
```
yarn
```bash
yarn add @jumamiller/vue2-toastr
```

```javascript
import CxltToastr from '@jumamiller/vue2-toastr'

Vue.use(CxltToastr)
```

```javascript
var toastrConfigs = {
    position: 'top right',
    showDuration: 2000
}
Vue.use(CxltToastr, toastrConfigs)
```


|          |            |             |
| --------- |:----------:|------------:|
| successColor     |   String   |     success |
| infoColor        |   String   |        info |
| warningColor     |   String   |     warning |
| errorColor       |   String   |       error |


```javascript
import 'cxlt-vue2-toastr/dist/css/@jumamiller/vue2-toastr.css'
```
style
```javascript
<style src="cxlt-vue2-toastr/dist/css/@jumamiller/vue2-toastr.css"></style>
```
### 使用组件
```javascript
this.$toast.success({
    title:'',
    message:''
})

this.$toast.success('message')
```

@jumamiller/vue2-toastr

| types     |
|-----------|
| success   |
| info      |
| warn      |
| error     |
| removeAll |

### type

* `success`
* `info`
* `warning`
* `error`

### position

* `top right`
* `bottom right`
* `bottom left`
* `top left`
* `top center`
* `bottom center`
* `top full width`
* `bottom full width`

### icon

### showMethod
  * `bounce`
  * `flash`
  * `pulse`
  * `rubberBand`
  * `shake`
  * `headShake`
  * `swing`
  * `tada`
  * `wobble`
  * `jello`
  * `bounceIn`
  * `bounceInDown`
  * `bounceInLeft`
  * `bounceInRight`
  * `bounceInUp`
  * `fadeIn`
  * `fadeInDown`
  * `fadeInDownBig`
  * `fadeInLeft`
  * `fadeInLeftBig`
  * `fadeInRight`
  * `fadeInRightBig`
  * `fadeInUp`
  * `fadeInUpBig`
  * `flipInX`
  * `flipInY`
  * `lightSpeedIn`
  * `lightSpeedOut`
  * `rotateIn`
  * `rotateInDownLeft`
  * `rotateInDownRight`
  * `rotateInUpLeft`
  * `rotateInUpRight`
  * `hinge`
  * `rollIn`
  * `zoomIn`
  * `zoomInDown`
  * `zoomInLeft`
  * `zoomInRight`
  * `zoomInUp`
  * `slideInDown`
  * `slideInLeft`
  * `slideInRight`
  * `slideInUp`

### hideMethod

  * `bounce`
  * `flash`
  * `pulse`
  * `rubberBand`
  * `shake`
  * `headShake`
  * `swing`
  * `tada`
  * `wobble`
  * `jello`
  * `bounceOut`
  * `bounceOutDown`
  * `bounceOutLeft`
  * `bounceOutRight`
  * `bounceOutUp`
  * `fadeOut`
  * `fadeOutDown`
  * `fadeOutDownBig`
  * `fadeOutLeft`
  * `fadeOutLeftBig`
  * `fadeOutRight`
  * `fadeOutRightBig`
  * `fadeOutUp`
  * `fadeOutUpBig`
  * `flipOutX`
  * `flipOutY`
  * `rotateOut`
  * `rotateOutDownLeft`
  * `rotateOutDownRight`
  * `rotateOutUpLeft`
  * `rotateOutUpRight`
  * `rollOut`
  * `zoomOut`
  * `zoomOutDown`
  * `zoomOutLeft`
  * `zoomOutRight`
  * `zoomOutUp`
  * `slideOutDown`
  * `slideOutLeft`
  * `slideOutRight`
  * `slideOutUp`

```bash
git clone xxx
cd @jumamiller/vue2-toastr
yarn
npm run dev
```


PayPal : jumamiller
