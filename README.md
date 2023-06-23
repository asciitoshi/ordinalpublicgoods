# Ordinal Public goods
A list of resources (js libraries, etc) inscribed on bitcoin. Feel free to create a pull request to add to it. Its just text so anyone can do it!

Caution: These libraries are NOT vetted and may contain issues/malware. Please be cautious when opening and using these files and look at the source. 

| Library | Inscription ID | Format | Notes | Source | 
| --- | --- | --- | --- | --- |
| Three.js | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | to extract and use: inscription.split("\n")[32] fflate.strFromU8(fflate.gunzipSync(new Uint8Array(Array.from(atob(d3)).map((char)=>char.charCodeAt(0))))) |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| gunzip in fflate | 2dbdf9ebbec6be793fd16ae9b797c7cf968ab2427166aaf390b90b71778266abi0 | gzip | need to do inscription.split("\n")[28] |  [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| p5.js | 255ce0c5a0d8aca39510da72e604ef8837519028827ba7b7f723b7489f3ec3a4i0 | gzip | need to unzip | [onchain monkey](https://github.com/metagood/OCM-Dimensions/blob/main/README.md)
| html2canvas 1.4.1 | be2585187c2e016b654ecc1f207fa73c38e55eee404cdf709346c4511689d24ai0 | none | | [king bootoshi](https://twitter.com/KingBootoshi/status/1670534828922400768?s=20)
