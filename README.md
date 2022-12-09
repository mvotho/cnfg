# cnfg

The cnfg service is a system that allows users to mint a non-fungible token (NFT) that maps to an off-chain URL. This URL contains a flat file JSON with key-value pairs of common settings, such as display name, avatar, language, font size, and dark mode preferences. Additionally, the URL contains pointers to encrypted off-chain datastores for sensitive information, such as email address and notification preferences.

When a user connects their wallet to an app or website, their Service Config is automatically imported and any sensitive data can be requested by the app and approved by the user with a single click. This system can be implemented using the Ethereum Name Service (ENS), but using a JSON format allows for extensibility and lower barriers to permissionless innovation.