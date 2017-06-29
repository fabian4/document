# 数据库引擎管理

## 查看数据库引擎列表

即数据库类型，如 mysql、mongo 等。

### 命令行使用

``` bash
  trove datastore-list
```

### 示例

``` bash
  # trove datastore-list
  +--------------------------------------+-------+
  | ID                                   | Name  |
  +--------------------------------------+-------+
  | c8128359-e1dd-45df-abb0-2ee2aaa9377e | mysql |
  +--------------------------------------+-------+
```

## 查看数据库引擎版本列表

数据库引擎版本，如 mysql 有 5.5、5.6 等。

### 命令行使用

``` bash
  trove datastore-version-list <datastore>
```

### 示例

``` bash
  # trove datastore-version-list mysql
  +--------------------------------------+------+
  | ID                                   | Name |
  +--------------------------------------+------+
  | 35b4c566-935c-4606-b077-20b90f2bf5df | 5.5  |
  +--------------------------------------+------+
```