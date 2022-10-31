# MutexDelay-1.0 :watch:
Straightforward library that allows to easily delay a method call, and to avoid multiple sources making unnecessary multiple calls to the same function for efficiency. Hence, behaves like a mutex over delayed code.

### API Overview
|Name|Description|
|:--|:--|
| :Embed(object) | Adds the library methods to your object. |
| :Delay(time, method [,args]) | Calls the given `method` after a certain `time` with the given `args`. Locks the `method` from further calls until complete.  |
| :Delaying(method) | Whether the `method` is currently locked from further calls. |
