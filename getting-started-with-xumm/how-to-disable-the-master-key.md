---
description: Disabling the Master key on an XRPL account
cover: ../.gitbook/assets/Large rock with Lock.jpg
coverY: 168
---

# How to disable the Master key

### Why disable the Master key?

There are two main reasons why you would want to disable the Master key for an XRPL account:

* Your account has been compromised
* You want to configure your account so that you can only sign and submit transactions using a regular keyed account.&#x20;

### Before you get started

You should be aware of the following before you proceed:

1\) To disable the master key pair, **you must use the master key pair.**&#x20;

2\) Your account must have at least one method of authorizing transactions other than the master key pair. e.g. - assign a regular key or configure multi-signing.

3\) You should confirm that you have the correct account secret for your account.\
\
\<Enter link to article - How to check your account secret>

The XRP Ledger will not let you disable the Master key unless there is an alternate way to sign and submit transactions. This article explains how to do by adding a regular key to your account.

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">How to rekey your account</td><td></td><td></td><td><a href="how-to-disable-the-master-key.md">how-to-disable-the-master-key.md</a></td><td><a href="../.gitbook/assets/Large rock with Key.jpg">Large rock with Key.jpg</a></td></tr></tbody></table>

&#x20;



&#x20;

## Optional Step 4: Disable your master key ⚠️ <a href="#h_a7c3b8f5aa" id="h_a7c3b8f5aa"></a>

This is an additional step which will disable your master key.

⚠️ Warning ⚠️: You will not be able to access the XRP account using your master key hereafter. Only your regular key pair will be able to sign.

&#x20;

The only way to enable your master key is to import your master key again, just by upgrading the account from read only to full access read/write.

![](https://downloads.intercomcdn.com/i/o/231464654/28341805c635e28b2aae300a/Change+access.png)

&#x20;

After this step go to the [xrpl.services](https://xumm.community/) for the last step.

Under the option for Account Set there is a checkbox Disable Master Key, check it and then you are good to go to sign that transaction using the account you have just re-keyed and you want to delete the account with. It will look like this:

![](https://downloads.intercomcdn.com/i/o/231263470/1f1aa4814561f48863ee2c1d/Schermafbeelding+2020-07-28+om+20.54.19.png)

When you have signed the transaction your account is now fully re-keyed and is not able to sign using its own master key anymore.

If, for whatever reason, your regular key gets compromised and the master key is not, you can set a new regular key using a tool like [xrpl.services](https://xumm.community/) to regain control of your account.

&#x20;If you already have a regular key pair with an XRP account you can just import your XRP account as a read-only account and the regular key pair as a full read/write account and you're set to go!

&#x20;&#x20;

Fully sign now with the regular key pair that you've just created 🎉

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the [<mark style="color:blue;">**Xumm Support xApp**</mark>](https://xumm.app/detect/xapp:xumm.support?ref=helpcenter) in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.
