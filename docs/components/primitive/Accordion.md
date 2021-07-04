# UAccordion

## Properties

### Title
* Type: String


### variant

* type: String
* default: Shadowed
* available values: shadowed, bordered, side bordered, clean, different border,...

### tooltip
* Type: String

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

### IconBeforClick
* Type: String
* default: arrow-start
* available values: arrow-start, plus, arrow-right-slim,...

### IconAfterClick
* Type: String
* default: arrow-down
* available values: arrow-down, minus,arrow-down-slim,...


## Methods

### Click
### ClickItems
    * point: Automatic submission of clicked item ID
### MouseOverItems
    * point: Automatic submission of mouse over item ID



## Examples

```html
<u-accordion variant="shadowed"   visible="true" Enable="true"  @Click="" >
  <u-accordion-Items Title="Item One" IconBeforclick="arrow-start" IconAfterClick="arrow-down"  CurrentActive="true" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" >
    <p> Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute </p>
  </u-accordion-Items>
  
  <u-accordion-Items Title="Item Two" IconBeforclick="arrow-start" IconAfterClick="arrow-down"  CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" >
    <ul>
      <li> One </li>
      <li> Two </li>
      <li> Tree</li>
    </ul>
  </u-accordion-Items>
  
   <u-accordion-Items Title="Item Tree" IconBeforclick="plus" IconAfterClick="minus"  CurrentActive="false" visible="true" Enable="true"    tooltip="" @ClickItems="" @MouseOverItems="" >
      Sample
  </u-accordion-Items>
  
</u-accordion>
```
