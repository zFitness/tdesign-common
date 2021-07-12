# Tree 树

用于承载有父子关系的结构化内容，提供内容层级的展示。

### 何时使用

当需要操作的内容需要分层展示信息时使用，如文件结构、组织架构、地理行政区等。

## 组件类型

在TDesign中，提供 5 种不同形式的树：基础树、带多选框的树、带操作功能的树、可自定义图标的树、带连接线的树

### 基础树

可承载存在父子关系的内容的展示，父节点带有展开/折叠操作，提供单个节点的选中标记。常用于系统目录结构、组织架构的展示。

{{ base }}

### 带多选框的树

在基础树结构上提供多选框控件，当需要对多个节点进行选择时使用，如选择组织架构中的多个人员。

{{ checkable }}

### 带操作功能的树

在基础树结构上提供针对节点的操作按钮，当需要对节点进行一系列操作时使用，如增、删、改。

{{ operations }}

### 自定义图标的树

可以对父节点上展开/折叠的图标进行自定义设计。当需要图标与信息名的含义匹配时使用，如文件夹的概念。

{{ icon }}

### 带连接线的树

将树中的父节点与其层级内的子节点进行连线。该用法针对子项层级较深且较多的情况，需要更明确表示从属关系。

{{ line }}

### 初始化展开全部

{{ expand-all }}

### 初始化展开第一级

{{ expand-level }}


### 互斥展开

{{ expand-mutex }}

### 可高亮

{{ activable }}

### 禁用状态

{{ disabled }}

### 异步加载节点

{{ load }}

### 展开时加载节点

{{ lazy }}

### 受控操作

{{ controlled }}

### 数据同步

{{ sync }}

### 过滤节点

{{ filter }}

### 空数据

{{ empty }}

### 自定义 label

{{ label }}

### 更新节点

{{ state }}