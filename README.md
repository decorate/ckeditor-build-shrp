CKEditor 5 Custom Shrimp Build Editor 
========================================

## Documentation

See:
* https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/frameworks/vuejs.html


## Quick start
```bash
npm install @team-decorate/ckeditor-build-shrp @ckeditor/ckeditor5-vue
```

And use it in your component

```vue

<template>
<ckeditor
	:editor="editor"
	v-model="editorData"
	:config="editorConfig"/>
</template>

<script>
import ShrpEditor from '@team-decorate/ckeditor-build-shrp'

export default {
	data() {
		return {
			editor: ShrpEditor,
			editorData: '<p>Content of the editor.</p>',
			editorConfig: {}
		}
	}
}
</script>
```

## default plugins

```
ClassicEditor.builtinPlugins = [
	Essentials,
	UploadAdapter,
	Autoformat,
	Bold,
	Italic,
	BlockQuote,
	CKFinder,
	EasyImage,
	Heading,
	Image,
	ImageCaption,
	ImageStyle,
	ImageToolbar,
	ImageUpload,
	Link,
	List,
	MediaEmbed,
	Paragraph,
	PasteFromOffice,
	Table,
	TableToolbar,
	Font,
	Alignment,
	Strikethrough,
	underline,
	Mention,
	ImageResize,
	ImageInsert
];
```


 ## Ck editor 5
**Ck Editor :**  Read more in the [CkEditor](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/development/custom-builds.html).

