# U-Alert

## Properties


### variant

* type: String
* default: primary
* available values: primary, secondary, danger, info, warning, success,light,purple,pink,dark,...

### visible

* type: boolean
* default: true

### HasCloseButton
* type: boolean
* default: false

### AlertHeading
* type: String
* DefaultView: false

### DisplayTime
* value type: int
* Type of time: Seconds
* default: unlimited

## Methods

### AfterClickCloseButton


## Examples

```html
<u-alert variant="info"   visible="true" HasCloseButton="true"   DisplayTime="10" @AfterClickCloseButton="">
  <span> Alert : Sample</span>
</u-alert>


<u-alert variant="danger"   visible="true" HasCloseButton="true"   AlertHeading="aditional Content!" >
  <p>Aww yeah, you successfully read this important alert message.</p>
	<hr>
	<p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</u-alert>

```
