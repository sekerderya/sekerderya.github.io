# sekerderya.github.io

The root of `https://sekerderya.github.io`. It only serves
[`.well-known/assetlinks.json`](.well-known/assetlinks.json), the Digital Asset Links file that lets the
[Maneki Merge](https://github.com/sekerderya/maneki-merge) Android app open the game full screen (a Trusted
Web Activity). Android looks for it at the root of the domain, so it can't live in the game's own Pages site.

How to fill in its fingerprints: `docs/PLAY_STORE.md` in the game's repository. `.nojekyll` makes Pages serve
the `.well-known` folder. The other sites under this domain live in their own repositories.
