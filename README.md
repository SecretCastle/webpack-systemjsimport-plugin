# webpack-systemjsimport-plugin

For `vue/cli`, this plugin rely on `html-webpack-plugin@3.2.0` in `vue/cli`


## options

| parameters | default | description | 
| ---- | ---- | ---- |
| include | {} | inject `<script type="systemjs-import">{"import": {}}</script>` in html head |

## output

head

```
<script type="systemjs-importmap'>
{
  "imports": {
    
  }
}
</script>
```


body

```
<script type="systemjs-module" src="[output bundle].js"></script>
```