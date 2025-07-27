# 📐 `size` Utility in Tailwind CSS


The `size` utility is a **shorthand for setting both width and height at once**.
It's equivalent to: w-* + h-*

## ✅ Syntax

```
size-0
size-px
size-1
size-2
...
size-96
size-full
size-screen
```


## 📦 Examples

```
<div class="size-10 bg-red-400"></div>     <!-- 2.5rem x 2.5rem box -->
<div class="size-24 bg-blue-400"></div>    <!-- 6rem x 6rem box -->
<div class="size-full bg-green-400"></div> <!-- 100% width and height -->
<div class="size-screen bg-yellow-400"></div> <!-- 100vw x 100vh -->
```


## 🧪 Arbitrary Values

You can also use arbitrary values with `size`:

```
size-[200px]
size-[50%]
size-[calc(100%-2rem)]
```


## ✅ Use Cases

* Circular avatars:

  ```
  <img class="size-16 rounded-full" src="..." />
  ```

* Responsive square containers:

  ```
  <div class="size-[25vw] bg-gray-200"></div>
  ```


## 🧠 Note

* If you want **independent control**, use `w-*` and `h-*`.
* If you want **equal width and height**, use `size-*`.


🔙 [Back to Home](../README.md)

