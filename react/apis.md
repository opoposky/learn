React v18.3.1  doc
VVG.


useActionState - This feature is available in the latest Canary  // 不常用的 api
useCallback  / useMemo
在JavaScript中，function(){}或()=>{}总是创建一个不同的函数，类似于 {} 对象字面值总是创建一个新对象。通常情况下，这不会是一个问题，但这意味着 function / {} 永远不会相同，memo 优化将不起作用。这就是 useCallback 派上用场的地方.

```js
function(){} //得到一个匿名函数
```

