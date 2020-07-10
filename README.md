# FileTemplate
文件模板

## Webstorm file config
### javascript/typescript
```

// 
// FileName ${NAME}
// ProjectName ${PROJECT_NAME}
//
// ComputerUser ${USER}
// Author 区区电脑
// Email 1573580882@qq.com
// Date ${DATE} ${TIME}
// Copyright © ${YEAR} ${USER}. All rights reserved.
//
//



```
### vue
```
<template>
    <div class="${NAME}">${NAME}</div>
</template>
<script>
// ${NAME}
let __this;
export default {
    name: '${NAME}',
    created() {
        __this = this;
    }
}
</script>
<style scoped lang="less">
.${NAME} {}
</style>
```


