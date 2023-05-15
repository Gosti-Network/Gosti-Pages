---
layout: default
---

## How Spriggan uses private DataLayer tables to authenticate and verify published content

Chia's DataLayer is an amazing tool capable of creating public and auditable decentralized databases like the Climate Action Data Trust. But it can also be used on a much smaller scale to authenticate and verify user data in a decentralized way.

If you are unfamiliar with what I am building, Spriggan is a platform for truly decentralized publishing of PC games, decentralized apps, and eventually other forms of media.

Using our open source tools, creators can create and manage their own private DataLayer data store of products, which can be shared with trusted marketplaces which provide a storefront and discoverability for their products. This private data includes torrent files and passwords to decrypt their content, which stay private between the creator, trusted marketplaces, and customers who have purchased the content.

Unless the owner of a DataLayer data store publishes a mirror, the data is not public. Only the hash of the data is put on the blockchain. It is however, publicly verifiable using that hash. Marketplaces and end users can always check the hash to be sure that the product they downloaded is exactly what the author published.

Using this system, simplifies publishing greatly because marketplaces do not have to care where their data came from, only that it is legitimate. User authentication is not necessary. When a marketplace receives an update for a product, or a request to list a new product, they only need to check that the hash of the data matches the hash on the blockchain to know that the update is legitimate.

For more information, or to get involved in the future of open source publishing, check out our github, or come say hi on our Discord.

[back](./)
