<div align="center"><img src="https://i.imgur.com/sbrRXkW.jpeg" /></div>

**A Telegram Auto Posting Package**

• `A Package Used To Post Memes, Gifs, Facts Etc Automatically To Your Channel On Telegram`

```bash
$ python3 -m pip install -U AutoPostTelegram
```

## Example

# To Post Single Anime Meme
```
import asyncio
from Stuffs import auto

x = auto(TOKEN)

x.animememe(chat="@AnimeMeme")
```

# To Post Anime Memes Infinity
```
import asyncio
from Stuffs import auto

x = auto(TOKEN)

while True:
    x.animememe(chat="@AnimeMeme")
    asyncio.sleep(5) #The Time Gap Of Your Post In Seconds
    x.animememe(chat="@AnimeMeme")
```

# Get Endpoints
```
from Stuffs import auto

x = auto(TOKEN)

print(x.endpoints())
```

# Known Issues
```
Issue: While Using Package To Post Infinity Memes Or Something The Other Function Of The Bot Is Stopped Working ( Because Of asycnio.sleep() )[ Can't Find Alternative To Fix If You Know Comment On This Commit]
```

# Recommended
```
Recommended To Use This Pacakge For Only To Auto Posting Feature
```
