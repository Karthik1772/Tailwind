# 📦 Tailwind CSS Padding & Margin Utilities

Tailwind provides utilities to control **spacing** inside (padding) and outside (margin) of elements, using a **scale-based system**.

## 📏 Spacing Scale

Tailwind uses a consistent scale like this (unit = `rem`):

```
0     = 0rem
0.5   = 0.125rem
1     = 0.25rem
1.5   = 0.375rem
2     = 0.5rem
2.5   = 0.625rem
3     = 0.75rem
3.5   = 0.875rem
4     = 1rem
5     = 1.25rem
6     = 1.5rem
7     = 1.75rem
8     = 2rem
9     = 2.25rem
10    = 2.5rem
11    = 2.75rem
12    = 3rem
14    = 3.5rem
16    = 4rem
20    = 5rem
24    = 6rem
28    = 7rem
32    = 8rem
36    = 9rem
40    = 10rem
44    = 11rem
48    = 12rem
52    = 13rem
56    = 14rem
60    = 15rem
64    = 16rem
72    = 18rem
80    = 20rem
96    = 24rem
px    = 1px
```


## 1>📥 Padding Utilities

Use `p` prefix for **padding** on all sides:

```
p-0
p-1
p-2
...
p-96
p-px
```

### Side-Specific Padding

```
pt-4    // padding-top
pr-2    // padding-right
pb-6    // padding-bottom
pl-3    // padding-left
```

### Axis-Specific Padding

```
px-4    // padding-left + padding-right
py-2    // padding-top + padding-bottom
```

---

## 2> 📤 Margin Utilities

Use `m` prefix for **margin** on all sides:

```
m-0
m-1
m-2
...
m-96
m-px
```

### Side-Specific Margin

```
mt-4    // margin-top
mr-2    // margin-right
mb-6    // margin-bottom
ml-3    // margin-left
```

### Axis-Specific Margin

```
mx-4    // margin-left + margin-right
my-2    // margin-top + margin-bottom
```


## ➖ Negative Margin

Add `-` before the class:

```
-m-1
-mt-2
-mx-4
```

## 🔁 Auto Margin (Centering elements)

Use `auto` keyword:

```
m-auto
mx-auto   // horizontal center (commonly used with fixed width)
```
