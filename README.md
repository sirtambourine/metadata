# 🐙 mimic metadata storage
Here you will find the public metadata for the existing strategies at [mimic.fi](https://.mimic.fi), feel free to contribute.

## Syncing with IPFS

After each commit to master, direct or as a result of a merged pull request, a
sync to IPFS is triggered. After the upload is complete the
[metadata.mimic.fi](https://metadata.mimic.fi) is updated automatically to
point to the latest IPFS cid.

We rely on [pinata.cloud](https://pinata.cloud) for the IPFS hosting, and on
[cloudflare](https://cloudflare-ipfs.com) for the the gateway proxy.

