# name_scope和 variable_scoped的作用

可以为其作用域中的节点的name添加一个或多个前缀，并使用这些前缀作为划分内部与外部op范围的标记。同时在TensorBoard可视化时可以作为一个整体出现（也可以展开）。并且name_scope可以嵌套使用，代表不同层级的功能区域的划分。

# name_scope和 variable_scoped的异同点

相同：在多级作用域时，他们的name都是会嵌套的 不同：对于相同的name，name_scope会自动生成后缀、创造了两个命名空间、而variable_scope则不会生成后缀、还是同一个命名空间。

