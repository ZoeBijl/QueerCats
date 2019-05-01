# Deploy Emojis To Pleroma

``` bash

MIX_ENV=prod mix pleroma.emoji ls-packs -m https://zoebijl.github.io/QueerCats/meta/pleroma/emoji-index/QueerCats/index.json
MIX_ENV=prod mix pleroma.emoji get-packs -m https://zoebijl.github.io/QueerCats/meta/pleroma/emoji-index/QueerCats/index.json QueerCats

```
