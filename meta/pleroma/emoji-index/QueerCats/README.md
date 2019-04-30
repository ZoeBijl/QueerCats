# Deploy Emojis To Pleroma

``` bash

MIX_ENV=prod mix pleroma.emoji ls-packs -m https://raw.githubusercontent.com/ZoeBijl/QueerCats/master/meta/pleroma/emoji-index/QueerCats/index.json
MIX_ENV=prod mix pleroma.emoji get-packs -m https://raw.githubusercontent.com/ZoeBijl/QueerCats/master/meta/pleroma/emoji-index/QueerCats/index.json QueerCats

```
