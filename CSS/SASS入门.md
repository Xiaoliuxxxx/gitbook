# 2.SASS入门

1. #### 使用变量
   
    - 1变量声明  
       变量使用关键字$声明，表明他是一个变量，如
       ```scss
      $highlight-color: #F90;
      ```
     
   - 2引用变量  
     将变量直接作为属性值使用，如：
     ```scss
     - $highlight-color: #F90;
        .selected {
            border: 1px solid $highlight-color;
        }
      //编译后
      .selected {
        border: 1px solid #F90;
      }
     ```
     
   - 3使用中划线还是下划线  
     sass并不想强迫任何人一定使用中划线或下划线，所以这两种用法相互兼容。用中划线声明的变量可以使用下划线的方式引用，反之亦然。
   
     ```scss
      $link-color: blue;
      a {
         color: $link_color;
     }
     //编译后
     a {
       color: blue;
     }
     ```
2. #### 嵌套CSS规则

3. #### 导入SASS文件

4. #### 静默注释

5. #### 混合器

6. #### 使用选择器继承