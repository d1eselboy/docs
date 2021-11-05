# Storage & Deletion

We are using IPFS to store information. It is a P2P file system that allows us to save information in a decentralized way across multiple devices. It also allows deduplicating information. For example, if you upload a picture 3 times, then you will see that 1 file is stored in the `Sync status` menu.

All the data you create will be stored locally on your device. That is why Anytype is working offline. After launching the app on another device data will be synced and stored there automatically except for files and video. They will be downloaded on-premise. So, when you add a 4k video on the desktop it will be streamed to your device from the backup node or desktop.

Currently, there is no way to physically delete the file from the device. At the moment there is only an object (page) archiving option that removes the page from the navigation. The real process of removing data from the device memory will be implemented later this year.

{% hint style="info" %}
**Good to know:** your product docs aren't just a reference of all your features! use them to encourage folks to perform certain actions and discover the value in your product.
{% endhint %}
