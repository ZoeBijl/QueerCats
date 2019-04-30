# Deploy Emojis To Pleroma

``` bash

MIX_ENV=prod mix pleroma.emoji ls-packs -m https://raw.githubusercontent.com/mcrosson/QueerCats/pleroma-emoji-pack/pleroma/emoji-index/QueerCats/index.json
MIX_ENV=prod mix pleroma.emoji get-packs -m https://raw.githubusercontent.com/mcrosson/QueerCats/pleroma-emoji-pack/pleroma/emoji-index/QueerCats/index.json queerCats

```
