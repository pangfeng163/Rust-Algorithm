# Rust Algorithm
## 开始之前
- 这里会用Rust实现常用的算法和数据结构,每个算法或数据都会单独创建一个新项目目录,并确保没有相互依赖,毕竟熟能生巧
- 使用这些请确保有Rust和一些基础知识的储备(比如手头有一本算法书可以翻阅)
## 实现
  ### 二叉搜索树 ([rust-algorithm/bst/src/bst.rs](rust-algorithm/bst/src/bst.rs))
  - insert 插入操作
  - maximum minimum 最大值,最小值
  - predecessor successor 前驱,后继
  - search delete 查询,删除
  ### 红黑树 ([rust-algorithm/rbtree/src/rbtree.rs](rust-algorithm/rbtree/src/rbtree.rs))
  - 创建 (       [rust-algorithm/rbtree/src/rbtree/create.rs](rust-algorithm/rbtree/src/rbtree/create.rs))
  - 查找 ([rust-algorithm/rbtree/src/rbtree/find.rs](rust-algorithm/rbtree/src/rbtree/find.rs))
  - 插入 ([rust-algorithm/rbtree/src/rbtree/update.rs](rust-algorithm/rbtree/src/rbtree/update.rs))
## 文档
- 暂时没有文档来说明这些算法实现,但是你可以查阅算法书籍和仔细阅读源码实现
## 正确性
- 这些算法的正确性都是靠测试保证的,但难免没能覆盖所有可能,所以若发现实现有错误,请提出issue，让我们共同进步
## 进步
- 毕竟个人水平有限,若对于这些算法你有更好的实现,也欢迎分享,让我们共同进步
