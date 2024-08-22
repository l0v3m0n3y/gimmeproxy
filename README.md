# gimmeproxy
JavaScript library for gimmeproxy.com
# main
```js
async function main(){
    const {gimmeproxy} = require('./gimmeproxy');
    const gimme= new gimmeproxy();
    let req=await gimme.get_proxy('type')
    console.log(req)
}
main()
```
