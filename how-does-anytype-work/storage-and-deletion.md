# Storage & Deletion

## Storage

We are using a private [IPFS](https://docs.ipfs.io/concepts/what-is-ipfs/) network and [ThreadDB](https://docs.textile.io/threads/) to handle storage. It is a Peer-To-Peer file system that facilitates decentralized storage of data across devices. Furthermore, we use the deduplication feature to reduce storage. E.g. If the same picture is uploaded three times, there is only one image copy stored to reduce storage consumption.

Anytype is Offline first; hence all data that you create will be stored locally first. After that, the data is synced to the backup node and your devices for redundancy.&#x20;

### Media

Media files are not directly downloaded in overall syncing to save bandwidth. Instead, when that file is requested, it is streamed to your device from the backup node or your devices on the network. E.g. If you have a 4k Video, it will be streamed from the backup node or P2P devices to your device.

So when you open object with  image it downloads, when you press play on video & audio it begin to download. After that this file will be stored in application cache.

{% hint style="info" %}
[we-are-using-ipfs.-what-is-that.md](../faqs/we-are-using-ipfs.-what-is-that.md "mention")
{% endhint %}

## Deletion

![](<../.gitbook/assets/Screenshot 2021-11-02 at 16.25.23.png>)

At the moment you can delete only [objects.md](../fundamentals/objects.md "mention") that you create inside Anytype. At first you can move them to bin that will remove the them from navigation. At second you can remove them completely from all devices. All your devices will  also delete them from Anytype when get online.&#x20;

{% hint style="warning" %}
This action do it irrevocably, so please be careful.&#x20;
{% endhint %}

### Media

{% hint style="warning" %}
Objects like Media and those that come with Anytype (Types, Relations) might be deleted in further releases.
{% endhint %}

You can delete all the content via clear cache option in iOS and Android. This will completely remove all the data and will force app to sync once again completely. Since the media download works on-premise (take a look on[#media-1](storage-and-deletion.md#media-1 "mention")) you will remove all cached media and clear some storage.