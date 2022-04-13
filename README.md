# SCSS i18n mixin

This mixin package need to migrate projects with i18n supports to CSS local properties.  
Recommendation for usage with `scss-replacer`

## CSS properties

### Supported

```
'float'
'inset'
'size'
'margin'
'padding'
'border'
'text-align'
```

### Incoming

```
'box-shadow'
```

## Possible problems

Known problems:

- Not resolve problem with polyfills and using `[dir]` in `@keyframe`
