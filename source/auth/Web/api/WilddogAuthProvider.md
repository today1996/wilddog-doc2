
title: WilddogAuthProvider
---

WilddogAuthProvider 是邮箱和手机号认证方式的 Provider 类。

## 构造器
### new WilddogAuthProvider()

**定义**

继承自 [Provider](/auth/Web/api/Provider.html)

</br>

------


## 属性

### providerId

**定义**

```js
string
```
</br>

------

## 方法

### emailCredential

**定义**

```js
emailCredential(email, password)
```

**参数**

| 参数名      | 说明             |
| -------- | -------------- |
| email    | string 类型，邮箱地址 |
| password | string 类型，密码信息 |

**返回值**

[wilddog.auth.Credential](/auth/Web/api/Credential.html)

</br>

------

## 方法

### phoneCredential

**定义**

```js
phoneCredential(phone, password)
```

**参数**

| 参数名      | 说明             |
| -------- | -------------- |
| phone    | string 类型，手机号 |
| password | string 类型，密码信息 |

**返回值**

[wilddog.auth.Credential](/auth/Web/api/Credential.html)

</br>

------