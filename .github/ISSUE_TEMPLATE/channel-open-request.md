---
name: Channel Open Request
about: Request incoming liquidity to your node
title: "[CHANNEL-REQUEST]"
labels: channel-request
assignees: WeebDataHoarder

---

## Your Node
https://1ml.com/node/[your_node_publickey]

Describe what your node is for, activity, and why you want incoming liquidity.

### Feature List
Mark any that you have setup and enabled. These are not required items, just check the ones that apply.

* [ ] [Anchor outputs / anchor commitments](https://bitcoinops.org/en/topics/anchor-outputs/)
* [ ] [WUMBO channels](https://bitcoinops.org/en/topics/large-channels/)
* [ ] Automatic channel balancing
* [ ] Automatic fee scaling
* [ ] Low channel commitment reserve
* [ ] Battery-backed
* [ ] Redundant internet uplink
* [ ] 24/7 operation

---

### ⚠️ Safety Checklist ⚠️
These items here are for your own safety and not require recovery assistance in case the worst happens to any node.

* [ ] Regularly check and upgrade node software for new features / patches
* [ ] Backed up (or written down) own node seed / entropy: _BIP39_, _[aezeed (lnd)](https://github.com/lightningnetwork/lnd/blob/master/docs/safety.md#aezeed)_, _[hsm_secret (c-lightning)](https://github.com/ElementsProject/lightning/blob/master/doc/BACKUP.md#hsm_secret)_
* [ ] Configured `Static Channel Backups (SCB, channel.backup)` / `Static Remote Key` and they are automatically stored elsewhere: _[SCBs (lnd)](https://github.com/lightningnetwork/lnd/blob/master/docs/safety.md#static-channel-backups-scbs)_, _[file-based backups (c-lightning)](https://github.com/ElementsProject/lightning/blob/master/doc/BACKUP.md)_
* [ ] _(Optional)_ Configured a Watchtower Client: _[Altruist Watchtower (lnd)](https://github.com/lightningnetwork/lnd/blob/master/docs/watchtower.md)_, _[BOLT13 / teos (c-lightning)](https://github.com/talaia-labs/python-teos/tree/master/watchtower-plugin)_

---

### Liquidity Details
* **Amount in satoshi**: 2000000 (minimum 2M satoshi, maximum depends)
* **Expected duration**: 3 months
* **Public channel**: Yes/No (public is a routing channel visible to everyone, private channels do not get announced)

### Additional notes
Add any other notes here.
