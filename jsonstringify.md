## the rest params of javascript API JSON.Parse and JSON.stringify
```javascript
JSON.parse(obj,function(key,value){
  if(!value){
    return undefined;
  }
  return value;
})
JSON.stringify(obj,function(key,value){
  if(!value){
    return undefined;
  }
  return value;
},'...')
```
