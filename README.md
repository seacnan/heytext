### 用户注册

- 方法描述：用户注册

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  | 字段 |  说明  |  类型   | 备注 | 是否必填 |
  | :--: | :----: | :-----: | :--: | :------: |
  | type |  类型  | String  | reg  |    Y     |
  | user | 用户名 |   int   |      |    Y     |
  | pass |  密码  | varchar |      |    Y     |


### 用户登录

- 方法描述：用户登录

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  | 字段 |  说明  |  类型   | 备注  | 是否必填 |
  | :--: | :----: | :-----: | :---: | :------: |
  | type |  类型  | String  | login |    Y     |
  | user | 用户名 |   int   |       |    Y     |
  | pass |  密码  | varchar |       |    Y     |

### 用户修改昵称


- 方法描述：用户修改昵称

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  | 字段 |  说明  |  类型   |    备注    | 是否必填 |
  | :--: | :----: | :-----: | :--------: | :------: |
  | type |  类型  | String  | changeNick |    Y     |
  | user | 用户名 |   int   |            |    Y     |
  | pass |  密码  | varchar |            |    Y     |
  | nick |  昵称  | String  |            |    Y     |

### 用户修改头像


- 方法描述：用户修改头像

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  | 字段 |  说明  |  类型   |    备注    | 是否必填 |
  | :--: | :----: | :-----: | :--------: | :------: |
  | type |  类型  | String  | changeLogo |    Y     |
  | user | 用户名 |   int   |            |    Y     |
  | pass |  密码  | varchar |            |    Y     |
  | file |  头像  |  file   |            |    Y     |

### 用户投稿


- 方法描述：用户投稿

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  |  字段   |  说明  |  类型   | 备注 | 是否必填 |
  | :-----: | :----: | :-----: | :--: | :------: |
  |  type   |  类型  | String  |  up  |    Y     |
  |  user   | 用户名 |   int   |      |    Y     |
  |  pass   |  密码  | varchar |      |    Y     |
  |  label  |  标签  | String  |      |    Y     |
  | content |  内容  | String  |      |    Y     |
  |  file   |  图片  |  file   |      |    Y     |


### 获取指定用户投稿列表

- 方法描述：获取指定用户投稿列表

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  | 字段 |  说明  |  类型   |   备注   | 是否必填 |
  | :--: | :----: | :-----: | :------: | :------: |
  | type |  类型  | String  | userData |    Y     |
  | user | 用户名 |   int   |          |    Y     |
  | pass |  密码  | varchar |          |    Y     |
  | page |  页码  |   int   |          |    Y     |


### 获取投稿总列表

- 方法描述：获取投稿总列表

- URL地址：http://ss.wyouw.cn/ajax.php

- 请求方式：POST

- 请求参数：

  | 字段 | 说明 |  类型  | 备注 | 是否必填 |
  | :--: | :--: | :----: | :--: | :------: |
  | type | 类型 | String | data |    Y     |
  | page | 页码 |  int   |      |    Y     |

