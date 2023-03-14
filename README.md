---
description: 'Building on Zukeswap and need help? let us know.'
---

## Building on ZukeSwap

## **ZukeSwap Contracts:**

**Router Address**: `0xeCaf4708d2027A071d24A32F4409E57f7cBACFA1`

**Factory Address**: `0xc738bE6fE1A54d7B0F6e4C3262a46a002aC2508e`

**Multicall Address**: `0x474a0768AeE3D378356524F331235b3e5fD21416`

## How to get your token LOGO on Zukeswap:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> * **File Extension**: `png` . Uppercase `PNG` is considered invalid
> * **File Name**：`logo.png`
> * **Size**: `256px by 256px`
> * **Background**: Transparent is a must

### 2. Token Information File <a id="2-token-information-file"></a>

> * Fork the repository and add the token information (example below) to zukeswap.tokenlist.json
> * Create a folder under assets/{tokenAddress}
> * Add the token icon (logo.png) under the folder created in the previous step
> * Add the token information in the zukeswap.tokenlist.json file, in the format shown below

The sample below shows what information has to be included on the `zukeswap.tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.  
The contract address should follow the checksum address format \(see next requirement\).

```
{
       "chainId":15551,
       "address":"",
       "name":"ZukeSwap Token",
       "symbol":"ZUKE",
       "decimals":18,
       "logoURI":""

},

``` 

The Pull request will be screened before it gets added to the repository. In order to get approved, your submission must meet the following requirements.

* **Project has a website.**
* **Has a social media presence.**
* **Project must have some trading volume (ie. > $ 2k).**
* **Verified Contract on LOOP Explorer.**
* **Detailed Token Information.**
