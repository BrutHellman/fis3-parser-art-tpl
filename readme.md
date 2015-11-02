

##Usage


```javascript
//fis-conf.js for fis3

fis.match('**.atpl', {
    parser: fis.plugin('art-template', {
        native: false,
        ext 'atpl'
    }),
    rExt: 'html'
})

```


  $ fis3 release -d ./output

