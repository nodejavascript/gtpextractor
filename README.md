# gtpextractor

Google Takeout hands you your photos as a pile of dated folders with JSON sidecars attached. This is the
extractor that turns that pile back into something a person can actually use — dates taken from the metadata
rather than the folder name, and no photo left behind twice.

**Status: the licence is in place; the source has not been published yet.** This repository contains only
[LICENSE](./LICENSE) today, and this README will say so until that changes.

## What it is for

- Reading a Google Takeout export without flattening it into an unusable single folder.
- Taking each photo's real date from its sidecar metadata.
- Finding the duplicates the export creates when a photo lives in more than one album.

## Licence

MIT — see [LICENSE](./LICENSE).
