# Example Guide

## Add an example

Copy [template file](./modal.we) and build an example with [UI Gallery](#ui-gallery).  


## UI Gallery

We import a simple UI Gallery for consistent UI style. We recommend a new example can be composed with these UI components.

> Inspired by Bootstrap.

See [UI Gallery Example](./ui.we) for details.

![](http://gtms04.alicdn.com/tps/i4/TB1_v6FMpXXXXXfXXXX7XWpVpXX-278-519.gif)

### Reference:

0. [**ui-button**](./ui-button.we)
    * Attributes: 
        * `type`, ***default*** | primary | success | info | warning | danger | link 
        * `size`, ***large*** | middle | small
        * `value`
        * `disabled`, ***false*** | true
    * Event: 
        * `click`
0. [**ui-panel**](./ui-panel.we)
    * Attributes: 
        * `type`, ***default*** | primary | success | info | warning | danger 
        * `title`
        * `border`, number
0. [**ui-hn**](./ui-hn.we)
    * Attributes: 
        * `level`, ***1*** | 2 | 3 
0. [**ui-tip**](./ui-tip.we)
    * Attributes: 
        * `type`, ***success*** | info | warning | danger 
        * `value`, ***large*** | middle | small
        * `value`
        * `disabled`, ***false*** | true
0. [**ui-list-item**](./ui-list-item.we)
    * Event: 
        * `click`