# tiptap-extension-line-height

<h3 align="center">
    A line-height extension for tiptap paragraph.
</h3>

<br/>

<p align="center">
  <a href="https://www.npmjs.com/package/tiptap-extension-line-height">
    <img
     alt="NPM URL"
     src="https://img.shields.io/badge/npm-tiptapExtensionLineHeight?logo=npm">
  </a>
  <img
     alt="version"
     src="https://img.shields.io/badge/version-1.0.0-blue">
</p>

<br>

---

## Install

```shell
npm install tiptap-extension-line-height -S
```

## Usage

```js
import LineHeight from "tiptap-extension-line-height";

const editor = new Editor({
  element: document.querySelector(".editor"),
  extensions: [StarterKit, LineHeight],
});

const value = "1.25"; // 15px 0.25rem
editor.chain().focus().setLineHeight(value).run();
```

## Relations

**tiptap:** https://tiptap.dev/

**tiptap-appmsg-editor:** https://github.com/KID-1912/tiptap-appmsg-editor
