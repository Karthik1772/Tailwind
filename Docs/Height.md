# 📏 Tailwind CSS Height Utilities

Tailwind provides utilities to control the **height** of elements using fixed values, screen units, content-based values, fractions, and arbitrary values.



## 📦 Fixed Height

Use Tailwind’s spacing scale to apply fixed heights:

```
h-0        // 0rem
h-px       // 1px
h-0.5      // 0.125rem
h-1        // 0.25rem
h-1.5      // 0.375rem
h-2        // 0.5rem
...
h-96       // 24rem
```



## 📊 Fractional Heights (based on parent)

Use fractions to size elements relative to their parent height:

```
h-1/2      // 50%
h-1/3
h-2/3
h-1/4
h-2/4
h-3/4
h-1/5
...
h-11/12
h-full     // 100%
```



## 📱 Screen-Based Height

Set height relative to the viewport:

```
h-screen   // 100vh (viewport height)
```



## 📉 Minimum Height (`min-h-*`)

Set the **minimum height** of an element:

```
min-h-0
min-h-full         // 100%
min-h-screen       // 100vh
min-h-min          // min-content
min-h-max          // max-content
min-h-fit          // fit-content

// Custom
min-h-[150px]
```


## 📈 Maximum Height (`max-h-*`)

Control the **maximum height** of an element:

### ✅ Named Heights:

```
max-h-0
max-h-px
max-h-4
max-h-8
...
max-h-96
```

## 💬 Content-Based Height

Set height based on content or fit:

```
h-auto         // height based on content
h-min          // min-content
h-max          // max-content
h-fit          // fit-content
```

### ✅ Special Values:

```
max-h-full        // 100%
max-h-screen      // 100vh
max-h-min         // min-content
max-h-max         // max-content
max-h-fit         // fit-content
```

### ✅ Arbitrary Values:

```
max-h-[400px]
max-h-[80vh]
```

## 🧪 Arbitrary Heights (Custom)

Use square brackets to define custom heights:

```
h-[200px]
h-[50%]
h-[12rem]
h-[calc(100%-4rem)]
```


🔙 [Back to Home](../README.md)
