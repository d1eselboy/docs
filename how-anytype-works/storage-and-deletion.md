# Storage & Deletion

## Storage

We are using a private [IPFS](https://docs.ipfs.io/concepts/what-is-ipfs/) network and [ThreadDB](https://docs.textile.io/threads/) to handle storage. It is a Peer-To-Peer file system that facilitates decentralized storage of data across devices. Furthermore, we use the deduplication feature to reduce storage. E.g. If the same picture is uploaded three times, there is only one image copy stored to reduce storage consumption.

Anytype is Offline first; hence all data that you create will be stored locally first. After that, the data is synced to the backup node and your devices for redundancy. Larger files are not directly downloaded to save bandwidth; instead, when that file is requested, it is streamed to your device from the backup node or your devices on the network. E.g. If you have a 4k Video, it will be streamed from the backup node or P2P devices to your device.

## Deletion

Currently, there is no way to physically delete the file from the device. At the moment there is only an object (page) archiving option that removes the page from the navigation. The real process of removing data from the device memory will be implemented later this year.

{% hint style="info" %}
**Good to know:** your product docs aren't just a reference of all your features! use them to encourage folks to perform specific actions and discover the value in your product.
{% endhint %}
