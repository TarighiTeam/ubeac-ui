# UBreadcrumb

## Properties

## Title
* Type: String
### variant
* type: String
* default: clean
* available values: bg-light, border, border-bottom, breadcrumb-sublime

### tooltip
* Type:String

### visible

* type: boolean
* default: true

### Enable

* type: boolean
* default: ture

### CurrentActive
* type: boolean
* default: false
* point :Only one item can be active at a time

## Methods

### Click
### ClickItems
    * point: Automatic submission of clicked item ID
### MouseOverItems
    * point: Automatic submission of mouse over item ID



## Examples

```html
<b-readcrumb variant="bg-light"   visible="true" Enable="true"  @Click="" >
  <u-readcrumb-Items Title="Site name"   CurrentActive="false" visible="true" Enable="false"   tooltip="" @ClickItems="" @MouseOverItems="" />
  <u-accordion-Items  CurrentActive="true" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" >
      <a href="https://smarty.stepofweb.com/3.0.6/html_frontend/documentation/components-breadcrumbs.html">breadcrumbs documentation</a>
  </u-readcrumb-Items>
   <u-readcrumb-Items  CurrentActive="false" visible="true" Enable="true"    tooltip="" @ClickItems="" @MouseOverItems="" >
      <a href="https://smarty.stepofweb.com/3.0.6/html_frontend/documentation/components-breadcrumbs.html">breadcrumbs documentation</a>
  </u-readcrumb-Items>
  
</u-readcrumb>
```
