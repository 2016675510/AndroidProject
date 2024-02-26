# AndroidProject
#### **技术架构**

 ![技术架构图](..\技术架构图.png)

#### 数据存储

- 使用 sharedPreferences保存密码和自动登陆

- 使用SQLite数据库存储用户账号、便签和待办事项数据。

#### **功能设计**

 ![功能架构 (2)](..\AndroidProject\功能架构 (2).png)

##### 登陆注册模块

- 用户注册：
  -  使用用户名和密码进行用户注册。
  - 使用加密存储密码并实施安全措施。

- 权限管理：
  - 确保只有授权用户可以访问便签和待办事项。
  - 区分不同用户的权限。

##### 便签管理模块：

- 创建便签：
  - 提供界面以创建新便签，包括标题和内容，显示便签字数。

- 编辑和删除便签：
  - 允许用户编辑现有便签的标题和内容、清空内容，以及删除不需要的便签。

 

#####  待办事项管理模块：

- 创建待办事项：
  - 提供界面以创建新的待办事项，包括标题、描述、截止日期等信息。

- 编辑和删除待办事项：
  - 允许用户编辑和删除待办事项。
  - 标记待办事项为已完成：
  - 提供选项以标记已完成的待办事项。

##### 用户界面设计：

- 简洁清晰的界面：
  - 设计易于使用的用户界面，包括直观的操作和导航方式。
- 列表和卡片视图：
  -  以自定义ListView列表展示便签和待办事项。
