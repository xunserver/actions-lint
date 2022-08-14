## 功能
通过github action 实现代码的检查，包括eslint，stylelint和git commit message检查。

## 使用
```yml
...

- name: lint code
  uses: xunserver/actions-lint@master
  with: 
    ext: '.js,.ts,.vue' # default .js,.jsx,.ts,.tsx,.vue

...
```

## 功能和进度实现
- 完成技术调研
- 