# CKEditor-Markdown-Plugin
Markdown Plugin for CKEditor
This is a plugin for CKEditor, you can use `markdown` mode in CKEditor. Moreover, your article in `WYSIWYG` mode can be translated to `markdown`.

## Get Started
It needs [ckeditor standard version](http://download.cksource.com/CKEditor/CKEditor/CKEditor%204.4.7/ckeditor_4.4.7_standard.zip)
You can see the [DEMO](#)

## Usage
1. Create a folder named `markdown` in `ckeditor/plugins` path;
2. Download the source, and uncompress it in the folder;
3. Edit `config.js` (such as `ckeditor/config.js`):
```javascript
	config.extraPlugins = 'markdown'; // add this plugin
```

Enjoy it!


## Thanks
- [marked](https://github.com/chjj/marked)
- [to-markdown](http://domchristie.github.io/to-markdown)
- [codemirror](https://github.com/codemirror/CodeMirror)
