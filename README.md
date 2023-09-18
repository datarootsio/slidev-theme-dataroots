# Slidev Theme Dataroots

Based on the [`slidev-theme-meetup`](https://github.com/tboerger/slidev-theme-meetup), with some dataroots branding and colors! (Credits to them!)

## Install

Add the following frontmatter to your `slides.md`. Add the `slidev-theme-dataroots` project as a git dependency.

```md
---
theme: meetup
layout: intro
lineNumbers: false
themeConfig:
  title: Welcome to Slidev
  twitter: example
  github: example
  linkedin: example
---
```

This themes requires `qrious` to generate QR codes - you may need to install them manually.

## Examples

### Intro

```md
---
layout: intro
---
```

![intro slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/001.png)

### Presenter

```md
---
layout: presenter
photo: /images/tboerger.jpg
---
```

![presenter slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/002.png)

### Twocols

```md
---
layout: twocols
---
```

![twocols slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/003.png)

### Center

```md
---
layout: center
---
```

![center slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/004.png)

### Cover

```md
---
layout: cover
---
```

![cover slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/005.png)

### Window

```md
---
layout: window
---
```

![window slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/006.png)

### Default

```md
---
layout: default
---
```

![default slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/007.png)

### Qrcode

```md
---
layout: qrcode
url: https://github.com/datarootsio/slidev-theme-dataroots
---
```

![qrcode slide](https://raw.githubusercontent.com/datarootsio/slidev-theme-dataroots/main/example-export/008.png)

## Components

### CornerHex

Just hexagons shown within the slides.

```vue
<CornerHex class="absolute left-0 top-0 transform rotate-90" />
```

### WindowConsole

Display content in a terminal window.

```vue
<WindowConsole class="rounded-lg shadow-lg object-cover z-10">
  Content
</WindowConsole>
```

### LayoutHeader

General header part of every slide.

```vue
<LayoutHeader />
```

### LayoutFooter

General footer part of every slide.

```vue
<LayoutFooter />
```

## License

[MIT](https://opensource.org/license/mit/)
