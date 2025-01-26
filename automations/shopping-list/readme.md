## Use Case

When visting the shops I often forget if there is something on the shopping list (Todo list). This automation uses the zones within HA to define shops and once in the shop area for X minutes the automation triggers. 

This automation also alerts other members of the household that X person is at the shops (this feature was needed as we'd often forget to add things to the list). 


The automation will also clear the shopping list everyday (for items that have been marked as completed) as used in [Mobile>Home](https://github.com/mintcreg/ha-config/tree/main/dashboard/mobile/home).

**Note; The below YAML will allow you to display the shopping list and hide the completed items** 

<details>

 <summary>YAML Code</summary>

 <br>

```yaml
type: todo-list
entity: todo.shopping_list
hide_completed: true
card_mod:
  style:
    .: |
      }
      ha-card.type-todo-list div.divider {
        display: none;
      }
      ha-button-menu {
        display: none;
      }
      ha-card.type-todo-list mwc-list#checked {
        display: none;
      }
      ha-icon-button.reorderButton,
      ha-icon-button.addButton {
        margin-top: -17px !important;
      }
      :host {
        --mdc-checkbox-ripple-size: 33px;
      }
      ha-check-list-item {
        min-height: 28px !important;  
      }
      p.empty::before {
        content: "There's nothing on the shopping list" !important;
        font-size: 10pt !important;
       }    
      p.empty {
        /* There are probably more elegant ways to do this :) */
        font-size: 0 !important;
      }
      ha-card.type-todo-list div:last-of-type h2::before {
        content: "Items to buy" !important;
        font-size: 11pt !important;
      }

      ha-card.type-todo-list div:last-of-type h2 {
        font-size: 0 !important; /* Hide original text */
      }
    ha-textfield:
      $: |
        .mdc-text-field {
          margin-top: -12px;
          margin-bottom: 5px;
          height: 50px !important;
        }
        .mdc-text-field__input {
          color: white !important;
        }
```
</details>


