﻿# NetCoreEx

Extended collection of packages that provide common structures, extensions, and helpers that can be used across many libraries, and applications.

<img src="https://raw.githubusercontent.com/prasannavl/NetCoreEx/master/Misc/Logo.png" width="64" alt="Logo"/>

**Nuget:**
> Install-Package NetCoreEx.[PackageName]

All packages fully support the **CoreCLR.**

### Goals

- Abstract as much framework-like structs, and classes that aren't a part of the BCL.
- Provide helpers, and extensions that are commonly re-implemented redundantly by several libraries, and frameworks.
- Abstract the concept of colors in a simple and elegant way that's binary compatible with C-data structures, with clean extensions for conversions.

### Packages

- **`NetCoreEx.Geometry`** - Contains common core geometries like Point, PointS, Rectangle, Size, RectangleF, SizeF and so on.
- **`NetCoreEx.BinaryExtensions`** - Pointers and numeric binary helpers.
- **`NetCoreEx.Colors`** - Color abstractions.

**Note:** - Starting from v3, all packages are `netstandard 1.4`, and `Source` nuget packages are no more.

### Current Features

- Common IntPtr operations (Example: Break IntPtr into low, and high, convert to int safely on both 32-bit and 64-bit safely, and so on)
- Common binary manipulations of int, long, etc (Example: get or set low and high value of int)
- Common geometric patterns like Rect, Point, Size, RectF, RectS with many in-built helpers for convenience.