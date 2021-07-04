# UCard

## Properties

### border

* Type: String
* default: clean
* available values: primary, success, danger, info , ...

### variant

* type: String
* default: clean
* available values: basic-card, grid-cards, card-variants, jarallax , ...

### Title

* type: String
* default: clean

### visible

* type: boolean
* default: true

### IconTitle

* Type: String
* Default :clean
* available :check,arrow-end,search,close,pencil,...

### HoverAnimated

* Type: String
* Default :clean
* available :hover-top,hover-right,hover-bottom,hover-left,noshadow,hover-zoom,...

### NumberColumns

* Type: Integer
* Default :1

### ItemImageUrl

* Type: String
* Default :clean

### ImagePosition

* Type :string 
* Default :clean
* available :top,right,bottom,left

### CurrentActive

* type: boolean
* default: false
* point :Only one item can be active at a time

### ClickItems
    * point: Automatic submission of clicked item ID
### MouseOverItems
    * point: Automatic submission of mouse over item ID

## Methods

### click

## Examples

```html
<u-card variant="basic-card"   visible="true"   @Click="" Title="Sample"   HoverAnimated="hover-top" Title="Sample" IconTitle="pencil" > 
   Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, 
</u-card>

<u-card variant="grid-cards"  NumberColumns="3"  visible="true"   @Click=""    HoverAnimated="hover-top"  > 
  <u-card-Items border="primary" CurrentActive="true" visible="true" @ClickItems="" @MouseOverItems="" CurrentActive="true" ItemImageUrl="http://Test" ImagePosition="top">
    <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute</p>
    <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute</p>
    <u-button variant="danger"   icon="pencil" text="more ..." />
    <u-button variant="info"   icon="pencil" text="add to basket" />          
  </u-card-Items>

  <u-card-Items border="success" CurrentActive="true" visible="true" @ClickItems="" @MouseOverItems="" CurrentActive="false" ItemImageUrl="http://Test" ImagePosition="top">
    <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute</p>
    <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute</p>
    <u-button variant="danger"   icon="pencil" text="more ..." />
    <u-button variant="info"   icon="pencil" text="add to basket" />          
  </u-card-Items>
  
  <u-card-Items border="success" CurrentActive="true" visible="true" @ClickItems="" @MouseOverItems="" CurrentActive="false" ItemImageUrl="http://Test" ImagePosition="top">
    <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute</p>
    <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute</p>
    <u-button variant="danger"   icon="pencil" text="more ..." />
    <u-button variant="info"   icon="pencil" text="add to basket" />          
  </u-card-Items>
  
</u-card>
```
