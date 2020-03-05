# my-vue-library

## Project setup
```
npm install
```


### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```
### Example how to use plugin
Use in component file where to display table 
```
<VueNiceTable :columns="columns" :rows="rows" />

```

### Import component 
```
import VueNiceTable from "./components/VueNiceTable"
```
### Binding data with column name 
```
data() {
    return {
      columns: [
        {
          label: "filed_name",
          field: "field",
          tdClass: "text-left",
          thClass: "text-left"
        }
      ]
    };
  }
  ```
### Binding API Values 
```
computed: {
 rows: [],
}
```
### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
