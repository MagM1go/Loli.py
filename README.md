<h1 align="center">Loli api wrapper</h1>

#### pip install Loli-wrapper



Sync Example
--------------

```Python
from loli import LoliSync


loli = LoliSync()

print(loli.get_point('sfw', 'hug'))
```

Async example
--------------

```Python
from loli import LoliAsync
import asyncio


loli = LoliAsync()

async def main():
    print(await loli.get_point('sfw', 'hug'))

if __name__ == "__main__":
    asyncio.run(main())
```
