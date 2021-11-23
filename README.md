# aavegotchi-boilerplate

Example usage:

```
let r = await Moralis.Cloud.run("userGotchis",{"userAddress":"0xADA8aA2777825bc615C5F12126F8bf275E2245e5"})

let firstGotchi = r[0]
let firstGotchiID = r[0][0]
let firstGotchiSVG = await Moralis.Cloud.run("getGotchiSVG",{"tokenId":firstGotchiID})
console.log(firstGotchiSVG)
```


