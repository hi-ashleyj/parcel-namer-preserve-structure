# @hi-ashleyj/parcel-namer-preserve-structure

Tries to retain the existing file structure when using Parcel v2.
Modified from [the original](https://www.npmjs.com/package/@mischnic/parcel-namer-preserve-structure) to save filenames without the hash so things kinda all line up. Probably useful for someone else maybe.
If you still want the hashes - use the original. Cheers.

## Unmaintained
This repository is now archived and unmaintained, as I now mainly use Svelte and only use parcel for bundling typescript. I am leaving this package up, and publishing to npm as well for compatibility.

## Install:
For me, I generally use this package directly from github. If you want to install it the same way, use:
```sh
npm install --save-dev git+https://github.com/hi-ashleyj/parcel-namer-preserve-structure.git
```

An NPM install is coming, and will be available with `npm install @hi-ashleyj/parcel-namer-preserve-structure` soon.

## Usage:

Add a `.parcelrc` into your root directory (next to `package.json`):

```json
{
	"extends": "@parcel/config-default",
	"namers": ["@hi-ashleyj/parcel-namer-preserve-structure", "..."]
}
```
