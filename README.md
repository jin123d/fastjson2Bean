```
TypeInfo typeInfo = ReqClassUtils.getCallbackGenericType(callBack.getClass());
T t = ReqJsonUtils.parseHttpResult(typeInfo, jsonData);
```