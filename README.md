[![bower version](https://img.shields.io/bower/v/k-viewer-doc.svg)](https://libraries.io/bower/k-viewer-doc) 
[![open issues](https://img.shields.io/github/issues/k4ng%2Fk-viewer-doc.svg)](https://github.com/k4ng/k-viewer-doc/issues) 
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/k4ng/k-viewer-doc) 


# \<k-viewer-doc\>

a simple viewer document (docx, xlsx, pptx), ``` only for doc online ```.

<!--
```
<custom-element-demo height="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="k-viewer-doc.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<table width="100%">
    <tr>
        <td>
            <k-viewer-doc 
                source="dev-builds.libreoffice.org/tmp/test.docx" 
                label="Sampe data docx"></k-viewer-doc>
        </td>
        <td>
            <k-viewer-doc 
                source="dev-builds.libreoffice.org/tmp/test.xlsx" 
                label="Sampe data xlsx"></k-viewer-doc>
        </td>
        <td>
            <k-viewer-doc 
                source="dev-builds.libreoffice.org/tmp/test.pptx" 
                label="Sampe data pptx"></k-viewer-doc>
        </td>
    </tr>
</table>
```


## How to install

### bower

```markdown
bower install --save k-viewer-doc
```


## Properties

Data Attribute | Description | Default Value
-------------- | ----------- | -------------
label | For set label document | null 
source | ONLY URL | null


## Doc Sample

- dev-builds.libreoffice.org/tmp/test.docx (Writer)
- dev-builds.libreoffice.org/tmp/test.xlsx (Spreadsheets)
- dev-builds.libreoffice.org/tmp/test.pptx (Presentation)


## Change log

You can find a list of all changes for each release in the [change log](https://github.com/k4ng/k-viewer-doc/blob/master/CHANGELOG.md).


## Contributing

1. Fork it!
1. Create your feature branch: git checkout -b my-new-feature
1. Commit your changes: git commit -m 'Add some feature'
1. Push to the branch: git push origin my-new-feature
1. Submit a pull request :D


## License

[MIT License](https://github.com/dyazincahya/k-viewer-doc/blob/master/LICENSE) 
