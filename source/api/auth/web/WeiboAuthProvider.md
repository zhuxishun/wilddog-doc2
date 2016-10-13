
title: WeiboAuthProvider
---

WeiboAuthProvider 是新浪微博登录方式中provider类

## 构造器
###new WeiboAuthProvider()

**定义**

继承自[Provider](/api/auth/web/Provider.html)

**返回值**

[wilddog.Credential](/api/auth/web/Credential.html)

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

### credential

**定义**

```js
credential(arg1)
```

**参数**

| 参数名 | 说明 |
|---|---|
| arg1 | string类型，accessToken的值 |


</br>

------

### addScope

**定义**

```js
addScope(scope)
```

**参数**

| 参数名 | 说明 |
|---|---|
| scope| string类型，新浪微博OAuth的scope值 |
