---
theme: ./
layout: intro
highlighter: prism
lineNumbers: false
themeConfig:
  title: Welcome to Slidev
  twitter: datarootsio
  github: datarootsio
  linkedin: company/dataroots
---
# slidev-theme-dataroots

<carbon-arrow-right/> Create beautiful markdown presentations ❤️

---
layout: presenter
photo: https://dataroots.io/static/78eceac35830e54fbb8f5c7f956b19fa/d4a7d/ski-group.webp
---
# Presenter view

Some information

- Bullet points
- More bullets
- Bullets! <span animate-spin inline-block>🔫</span>

---
layout: twocols
---
# Twocols Example

(Boxes are just for demonstration purposes)

<div w-full border-2>
Before anything!
</div>

::left::

<div w-full border-2>

- This is the left column
- Sed diam voluptua
- With `::left::` prefix

</div>

::right::

<div w-full border-2>

- This is the right column
- Lorem ipsum dolor sit amet
- With `::right::` prefix

</div>

::bottom::

<div w-full border-2>

- At the bottom
- With `::bottom::` prefix

</div>
---
layout: center
---
# This is a centered slide with highlighted code

```ts {|1|2|3-5|6,9}
const aspectRatioPlugin = plugin(({ addUtilities }) => {
  const newUtilities = {
    '.aspect-none': {
      aspectRatio: 'none',
    },
    '.aspect-16-9': {
      aspectRatio: '16/9',
    },
    '.aspect-4-3': {
      aspectRatio: '4/3',
    },
    '.aspect-1-1': {
      aspectRatio: '1/1',
    },
  }
  addUtilities(newUtilities, ['responsive', 'hover'])
})
```

---
layout: cover
---
# This is a cover

---
layout: window
---
# Console

::window::

```ts
const aspectRatioPlugin = plugin(({ addUtilities }) => {
  const newUtilities = {
    '.aspect-none': {
      aspectRatio: 'none',
    },
    '.aspect-16-9': {
      aspectRatio: '16/9',
    },
    '.aspect-4-3': {
      aspectRatio: '4/3',
    },
    '.aspect-1-1': {
      aspectRatio: '1/1',
    },
  }
  addUtilities(newUtilities, ['responsive', 'hover'])
})
```

---
layout: default
---
# What is Slidev?

Slidev is a slides maker and presenter designed for developers, consist of the following features (and you can also animate it!)

<v-clicks>

- 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage
  
</v-clicks>

---
layout: qrcode
url: https://github.com/datarootsio/slidev-theme-dataroots
---
# Link to theme
