That looks **perfectly complete** already, Karthik! To make it fully polished and ready for your Tailwind CSS Learning Repo or personal documentation, here’s the finalized version with consistent formatting, slight enhancements, and no duplication:



# 📐 Tailwind CSS Width Utilities

Tailwind provides utilities to control the **width** of elements using fixed values, percentages, fractions, screen units, and arbitrary values.



## 📦 Fixed Width

Use Tailwind’s spacing scale to apply fixed widths:

```
w-0        // 0rem
w-px       // 1px
w-0.5      // 0.125rem
w-1        // 0.25rem
w-1.5      // 0.375rem
w-2        // 0.5rem
...
w-96       // 24rem
```



## 📊 Fractional Widths (based on parent)

Use fractions to size elements relative to their parent width:

```
w-1/2      // 50%
w-1/3
w-2/3
w-1/4
w-2/4
w-3/4
w-1/5
...
w-11/12
w-full     // 100%
```



## 📱 Screen-Based Width

Set width relative to the viewport:

```
w-screen   // 100vw (viewport width)
```



## 📉 Minimum Width (`min-w-*`)

Set the **minimum width** of an element:

```
min-w-0
min-w-full         // 100%
min-w-min          // min-content
min-w-max          // max-content
min-w-fit          // fit-content

// Custom
min-w-[150px]
```



## 📈 Maximum Width (`max-w-*`)

Control the **maximum width** of an element:

### ✅ Named Widths:

```
max-w-xs       // 20rem
max-w-sm       // 24rem
max-w-md       // 28rem
max-w-lg       // 32rem
max-w-xl       // 36rem
max-w-2xl      // 42rem
max-w-3xl      // 48rem
max-w-4xl      // 56rem
max-w-5xl      // 64rem
max-w-6xl      // 72rem
max-w-7xl      // 80rem
```

### ✅ Special Values:

```
max-w-none
max-w-full
max-w-min
max-w-max
max-w-fit
```

### ✅ Arbitrary Values:

```
max-w-[400px]
max-w-[90%]
```



## 🧪 Arbitrary Widths (Custom)

Use square brackets to define custom widths:

```
w-[300px]
w-[50%]
w-[10rem]
w-[calc(100%-2rem)]
```

