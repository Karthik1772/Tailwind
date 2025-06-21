# 🎨 Background Classes in Tailwind CSS

Tailwind provides powerful utilities to work with **backgrounds**, including colors, images, gradients, shadows, and blend modes.


## 🖼️ Add Image in Background

Use the `bg-[url()]` class:

```
<div class="bg-[url('/path/to/image.jpg')] bg-cover bg-center">
  <!-- content -->
</div>
```

Common modifiers:

```
bg-cover        // Scales image to cover container
bg-container      // Scales image to fit container
bg-center       // Centers image
bg-no-repeat    // Prevents repeating
bg-repeat       // Repeats image
```


## 🎨 Classes for Background Properties

* **Background color:**

```
bg-red-500
bg-green-100
bg-black
bg-white
bg-gradient-to-r
```

* **Positioning:**

```
bg-top
bg-center
bg-bottom
bg-left
bg-right
```

* **Attachment:**

```
bg-fixed
bg-local
bg-scroll
```

* **Repeat:**

```
bg-repeat
bg-no-repeat
bg-repeat-x
bg-repeat-y
```


## 🌈 Add Gradient

Use `bg-gradient-to-*` with color stops:

```
<div class="gradient bg-gradient-to-r from-purple-400 via-pink-500 to-red-500">
  <!-- gradient background -->
</div>
```

Variants:

```
bg-gradient-to-r   // right
bg-gradient-to-l   // left
bg-gradient-to-t   // top
bg-gradient-to-tr   // top right
bg-gradient-to-tl   // top left
bg-gradient-to-b   // bottom
bg-gradient-to-br   // bottom right
bg-gradient-to-bl   // bottom left
```

Use with:

```
from-*
via-*
to-*
```


## 🌫️ Add Shadow

Use `shadow` utilities to apply shadows:

```
shadow-sm
shadow
shadow-md
shadow-lg
shadow-xl
shadow-2xl
shadow-inner
shadow-none
```


## 🧪 Mix Blending

Control how elements blend with background:

```
mix-blend-normal
mix-blend-multiply
mix-blend-screen
mix-blend-overlay
mix-blend-darken
mix-blend-lighten
mix-blend-color-dodge
mix-blend-color-burn
mix-blend-hard-light
mix-blend-soft-light
mix-blend-difference
mix-blend-exclusion
mix-blend-hue
mix-blend-saturation
mix-blend-color
mix-blend-luminosity
```

Example:

```
<img src="/bg.jpg" class="mix-blend-overlay">
```


🔙 [Back to Home](../README.md)

