# `@hi-ashleyj/parcel-namer-preserve-structure`

Tries to retain the existing file structure when using Parcel v2.
Modified from the original to save filenames without the hash so things kinda all line up. Probably useful for someone else maybe.
If you still want the hashes - use the original. Cheers.

## Install:
I haven't packaged this on npm, because using a git repo is fine for my needs. If you want to install it, use:
```sh
npm install --save-dev git+https://github.com/hi-ashleyj/parcel-namer-preserve-structure.git
```

## Usage:

Add a `.parcelrc` into your root directory (next to `package.json`):

```json
{
	"extends": "@parcel/config-default",
	"namers": ["@hi-ashleyj/parcel-namer-preserve-structure", "..."]
}
```
