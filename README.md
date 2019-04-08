# React
React 笔记
 我们可以在 JSX 中使用 JavaScript 表达式。表达式写在花括号 {} 中。
 ```
 ReactDOM.render(
    <div>
      <h1>{1+1}</h1>
    </div>
    ,
    document.getElementById('example')
);
 ```
 问题： TypeError: Super expression must either be null or a function, not undefined
 解决： 说明你extend的那个函数没有导出相应的属性 `class Like extends React.Component`


 
