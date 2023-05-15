# Hstiro

## Hugo

```shell
.\bin\hugo.exe server
```

```shell
.\bin\hugo.exe version
Hugo Static Site Generator v0.62.0-6608F155 windows/amd64 BuildDate: 2019-12-23T10:26:18Z
```

## Vercel

```vercel.json
{
  "build": {
    "env": {
      "HUGO_VERSION": "0.83.1"
    }
  }
}
```

## Obsidian

```shell
# windows cmd
# plugin - Custom Attachment Location
mklink /j "images" "..\..\static\images"
```

### Replace

```
from obsidian
![](images/p/c.jpg)
to hugo
![](/images/p/c.jpg)
```

### Compress

compress stream
