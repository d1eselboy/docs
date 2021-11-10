# What additional account functionality do we have?

### Anytype ID

The Anytype ID is the regular identification method that is used to match with the keychain phrase. This allows us to understand if a user exists (just that) and can provision users to delete their encrypted data from our servers by request & consent that all their information will be deleted.

{% hint style="warning" %}
The Anytype ID serves no purpose except for verifying a users existence and cannot be used to recover an Account.
{% endhint %}

### Recovery

As Anytype does not store or know your private keychain passphrase, it is impossible to recover accounts for which the passphrase has been lost.

{% hint style="warning" %}
Please keep your passphrase secure and saved as it is the only way to access information inside Anytype.
{% endhint %}
