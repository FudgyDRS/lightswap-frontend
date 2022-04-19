## Adding Tokens

1. Fork the [PantherSwap Dex Frontend](https://github.com/pantherswap/lightswap-frontend/) repository on GitHub
2. Upload your **logo** in a 96\*96px transparent .png format to the `/public/images/coins` directory. Please name the logo as your symbol in uppercase.

3. Add your **token information** using the example format provided below to `pantherswap.json` in the `/src/constants/token/` directory.

4. Create a **pull request** detailing information about your project, website address, and contact details (telegram)

## Examples

**Logo format:**

`SYRUP.png`

**Token information format:**

```json
{
"name": "PantherSwap Token",
"symbol": "PANTHER",
"address": "0x1f546ad641b56b86fd9dceac473d1c7a357276b7",
"chainId": 56,
"decimals": 18,
"logoURI": "/images/coins/PANTHER.png"
},
```
