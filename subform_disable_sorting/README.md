### Subform: Disable row sorting

To prevent users from sorting rows in a Subform, place this empty function nuSortSubform() in you form's Custom Code field.
This will override the default sorting function.

```javascript
function nuSortSubform(s, c, e){
}
```
