# element-ui-
1.关键注意不要混写el里面的表单元素和普通表单元素

例如:
<pre>
   button和el-button
</pre>
可能出现问题:
1.如果使用在登陆按钮上会造成url多一次拼接，造成登陆俩次bug

