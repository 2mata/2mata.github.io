---
title: Component Shortcodes
description: Halaman contoh untuk component website 2mata terbaru
date: 2024-08-12
authors: Lord Rangga
draft: true
---

## Callout

{{< callout success="tip" >}}

Some React components, such as the header and the sidebar, implement different JavaScript logic when in mobile view.

If you change the breakpoint value in your custom CSS, you probably also want to update the invocations of the `useWindowSize` hook by [swizzling](https://docusaurus.io/docs/swizzling) the components it's used in and passing an explicit option argument.

{{< /callout >}}


```
{{</* callout success="tip" >}}

Inner content

{{< /callout */>}}
```




{{< callout warning="catatan" >}}

Some React components, such as the header and the sidebar, implement different JavaScript logic when in mobile view.

If you change the breakpoint value in your custom CSS, you probably also want to update the invocations of the `useWindowSize` hook by [swizzling](https://docusaurus.io/docs/swizzling) the components it's used in and passing an explicit option argument.

{{< /callout >}}




```
{{</* callout warning="catatan" >}}

Inner content

{{< /callout */>}}
```




{{< callout danger="penting" >}}

Some React components, such as the header and the sidebar, implement different JavaScript logic when in mobile view.

If you change the breakpoint value in your custom CSS, you probably also want to update the invocations of the `useWindowSize` hook by [swizzling](https://docusaurus.io/docs/swizzling) the components it's used in and passing an explicit option argument.

{{< /callout >}}



```
{{</* callout danger="penting" >}}

Inner content

{{< /callout */>}}
```

