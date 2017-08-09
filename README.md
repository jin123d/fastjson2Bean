参考 http://www.cnblogs.com/whoislcj/p/5533548.html

```
TypeInfo typeInfo = ReqClassUtils.getCallbackGenericType(callBack.getClass());
T t = ReqJsonUtils.parseHttpResult(typeInfo, jsonData);
```
