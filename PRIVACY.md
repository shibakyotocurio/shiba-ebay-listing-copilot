# Privacy Policy — SHiBA eBay Listing Copilot

**Effective date:** September 25, 2026

SHiBA eBay Listing Copilot is a personal/internal seller-assistance application used to help manage eBay listings for the account owner. This policy explains what information the application may access and how it is handled.

## Information the application may access

When the account owner authorizes the application through eBay OAuth, the application may access only the eBay data permitted by the scopes granted during authorization. Depending on the enabled features, this may include:

- eBay account identifiers and basic account information
- Listing, inventory, offer, business-policy, and shipping information
- Order or transaction information when required for an enabled workflow
- Product images and listing content supplied by the account owner
- OAuth access and refresh tokens required to communicate with eBay APIs

The application does not request or store the account owner's eBay password.

## How information is used

Information is used only to support seller workflows requested by the account owner, including:

- Preparing and validating listing data
- Creating or revising listings
- Uploading product images
- Applying shipping, payment, and return policies
- Retrieving listing, inventory, or account information needed for those workflows
- Performing testing in the eBay Sandbox environment

## Data storage and security

Application credentials, OAuth tokens, and private seller data are intended to be stored locally or in other private storage controlled by the account owner. Secrets are not intentionally published in this public repository.

The application is designed to use the minimum access needed for the requested workflow. The account owner should revoke eBay authorization and rotate credentials if unauthorized access is suspected.

## Sharing of information

The application does not sell personal information.

Data is transmitted to eBay only as necessary to use eBay APIs and seller services. Information may also be processed by infrastructure or services deliberately chosen by the account owner to operate the application. Those services are subject to their own privacy terms.

## Data retention

Data is retained only as long as needed for the seller workflow, recordkeeping, debugging, or legal obligations. OAuth credentials and locally stored data may be deleted by the account owner at any time when they are no longer needed.

## Access and revocation

The account owner can revoke the application's authorization through eBay account settings. After authorization is revoked, the application will no longer be able to obtain new access through that authorization unless the account owner authorizes it again.

## Children's privacy

This application is not directed to children and is intended for use by an adult eBay seller.

## Changes to this policy

This policy may be updated as the application changes. The current version will be published in this repository with its effective date.

## Contact

Questions about this privacy policy can be submitted through the public GitHub repository for SHiBA eBay Listing Copilot:

https://github.com/shibakyotocurio/shiba-ebay-listing-copilot
