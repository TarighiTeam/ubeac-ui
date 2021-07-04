# UDropdown

## Properties

### text
* Type:String
### DropdownType

* type: String
* default: dropdown-forms
* available values: dropdown-forms,extended-dropdowns, multi-level, mega, dropup,Split

### variant

* type: String
* default: primary
* available values: primary, pill, soft, danger, ...

### IconBeforclick
* Type:String
* default: arrow-start
* available values: arrow-start, plus, arrow-right-slim,...

### IconAfterClick
* Type:String
* default: arrow-down
* available values: arrow-down, minus,arrow-down-slim,...

### IconBeforMouseOver
* Type:String
* default: arrow-start
* available values: arrow-start, plus, arrow-right-slim,...

### IconAfterMouseOver
* Type:String
* default: arrow-down
* available values: arrow-down, minus,arrow-down-slim,...

### ItemsTitle
* Type:String


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
<u-dropdown variant="shadowed" text="Sample"  visible="true" Enable="true"  @Click="" IconBeforclick="arrow-start" IconAfterClick="arrow-down" tooltip="">
  <u-dropdown-tems  ItemsTitle="Corporate 1" CurrentActive="true" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" />
  <u-dropdown-tems  ItemsTitle="Corporate 2" CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" />  
  <u-dropdown-tems  ItemsTitle="Corporate 3" CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" />
</u-dropdown>

<u-dropdown variant="shadowed" text="Sample"  visible="true" Enable="true"  @Click="" IconBeforclick="arrow-start" IconAfterClick="arrow-down" tooltip="">
  <u-dropdown-tems  ItemsTitle="Corporate 1" CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" >
    <ul>
      <li>Corporate 1</li>
      <li>Corporate 2</li>
      <li>Corporate 3</li>
    </ul>
  </u-dropdown-tems>  
  <u-dropdown-tems  CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" >
    <a href="">Corporate 1</a>
  </u-dropdown-tems>   
  <u-dropdown-tems  CurrentActive="false" visible="true" Enable="true"   tooltip="" @ClickItems="" @MouseOverItems="" IconBeforMouseOver="arrow-start" IconAfterMouseOver="arrow-down" >
    <a href="">Corporate 2</a>
  </u-dropdown-tems>  
</u-dropdown>
```
