---
name: Channel Force-Close request
about: Ask for a force-close of an inactive channel due to data loss or other reason
title: "[CHANNEL-CLOSE]"
labels: DLP, channel-close
assignees: WeebDataHoarder

---

**Your Node**
https://1ml.com/node/[your_node_publickey]

**Reason of Force-Close**
Describe why you want to force-close a channel.

**Recovery Checklist**
Before submitting a Force-Close request, all these conditions have to apply to your channel/node.

* [ ] The channel/node has been inactive longer than 3 days and waited.
* [ ] Backups of your own node seed / entropy exist: own node seed / entropy: _BIP39_, _[aezeed (lnd)](https://github.com/lightningnetwork/lnd/blob/master/docs/safety.md#aezeed)_, _[hsm_secret (c-lightning)](https://github.com/ElementsProject/lightning/blob/master/doc/BACKUP.md#hsm_secret)_
* [ ] Tried to issue a force-close via Static Channel Backups / Static Remote Key feature (or do not have them): _[SCBs (lnd)](https://github.com/lightningnetwork/lnd/blob/master/docs/safety.md#static-channel-backups-scbs)_, _[file-based backups (c-lightning)[https://github.com/ElementsProject/lightning/blob/master/doc/BACKUP.md]_
* [ ] _(lnd only)_ Tried using [chantools](https://github.com/guggero/chantools) to create a "fake" channel.backup using information existing from historic backups / [1ML.com](https://1ml.com/) and tried recovery: [chantools fakechanbackup Documentation](https://github.com/guggero/chantools/blob/master/doc/chantools_fakechanbackup.md)
* [ ] Understand that the force-close transaction cannot send funds anywhere but what was agreed with your node when it was online.

---

**Proving node identity**
To know that your node identity is correct, you have these different ways to prove it. Do note your will still have to wait at least 3 days of inactivity.

* Sign a message using your node pubkey: sign a message containing the text `force-close channels with Lightning Hoarder, date [insert date here]`. Then provide this proof (text you signed + signature) as part of the issue.
* Prove contact details listed on your node name on the network. This can be a website, or social network.
* Prove contact details listed on [1ML](https://1ml.com/) or [amboss.space](https://amboss.space/) under your node details. This can be a website, or social network.
* Alternatively, if the node has been inactive for longer than 14 days force-channel requests may be issued at the discretion of the node operator upon request.
