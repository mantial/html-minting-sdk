# HTML MINTING SDK

Just copy or download the minter.html file and use it on your application. Be sure to use the configuration correctly.

## Mantial configuration

```json
{
    network: 'ropsten' | 'ethereum',
    collectionSlug: string,
    amount: number,
    showTitle: boolean,
    amountSelector: boolean,
    saleSelector: boolean,
    saleId: number,
    showDetails: boolean,
    showErrors: boolean,
    theme: any, // ---> MUI v5 theme
    styles: { // ---> allow inline styles applied as 'sx' to MUI components
        button: any,
        mintButton: any,
        switchNetworkButton: any,
        container: any,
        title: any,
        error: any,
        amount: any,
        iconButton: any,
        texts: any,
        success: any,
        minting: any,
        minterContainer: any,
        description: any,
        installMetamaskButton: any,
    },
    texts: {
        title: string,
        minting: string,
        success: string,
        buy: string,
        goBack: string,
        description: string,
        switchNetwork: string,
        installMetamask: string,
    },
};
```
