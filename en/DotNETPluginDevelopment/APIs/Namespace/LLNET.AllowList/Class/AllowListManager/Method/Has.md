# ð¡ AllowListManager.Has æ¹æ³

## å®ä¹

<br>

> è¿åä¸ä¸ªå¼ï¼è¯¥ææç¤ºæå®çç©å®¶æ¯å¦å­å¨äºç½ååä¸­ã

<br>

## éè½½
- 
    |||
    |-|-|
    |`Has(String)`|æ ¹æ®ç©å®¶åç§°æ¥æç©å®¶æ¯å¦å­å¨ã|
    |`Has(String, String)`|æ ¹æ®ç©å®¶åç§°ãXUIDæ¥æç©å®¶æ¯å¦å­å¨ã|
    |`Has(String, String, Int32)`|æ ¹æ®ç©å®¶åç§°ãXUIDæ¥æç©å®¶æ¯å¦å­å¨ã|

## Has(String)

<br>

C#
```cs
public bool Has(string name)
```
C++
```cpp
public:
    bool Has(System::String^ name)
```

- åæ°
  - `name` : [String](https://docs.microsoft.com/zh-cn/DotNET/api/system.string?view=net-6.0)  
    è¦æ¥æ¾çç©å®¶åç§°ã

<br>

- è¿å
  - [Boolean](https://docs.microsoft.com/zh-cn/DotNET/api/system.boolean?view=net-6.0)  
    å¦æ `name` åæ°ææåçç©å®¶å¨æ­¤ç½ååä¸­åºç°ï¼åä¸ºï¼åä¸º `true`ï¼å¦åä¸º `false`ã
  
<br>

## Has(String, String)

<br>

C#
```cs
public bool Has(string name, string xuid)
```
C++
```cpp
public:
    bool Has(System::String^ name, System::String^ xuid)
```

- åæ°
  - `name` : [String](https://docs.microsoft.com/zh-cn/DotNET/api/system.string?view=net-6.0)  
    è¦æ¥æ¾çç©å®¶åç§°
  - `xuid` : [String](https://docs.microsoft.com/zh-cn/DotNET/api/system.string?view=net-6.0)  
    è¦æ¥æ¾çç©å®¶XUID

<br>

- è¿å
  - [Boolean](https://docs.microsoft.com/zh-cn/DotNET/api/system.boolean?view=net-6.0)  
    å¦æ `name` åæ°ä¸ `xuid` åæ°ææåçç©å®¶å¨æ­¤ç½ååä¸­åºç°ï¼åä¸º `true`ï¼å¦åä¸º `false`ã
  
<br>

## Has(String, String, Int32)

<br>

C#
```cs
public bool Has(string name, string xuid, out int index)
```
C++
```cpp
public:
    bool Has(System::String^ name, System::String^ xuid, [Out]int% index)
```

- åæ°
  - `name` : [String](https://docs.microsoft.com/zh-cn/DotNET/api/system.string?view=net-6.0)  
    è¦æ¥æ¾çç©å®¶åç§°
  - `xuid` : [String](https://docs.microsoft.com/zh-cn/DotNET/api/system.string?view=net-6.0)  
    è¦æ¥æ¾çç©å®¶XUID
  - `index` : [Int32](https://docs.microsoft.com/zh-cn/DotNET/api/system.int32?view=net-6.0)  
    å¦æç´¢å¼å­å¨ï¼åå°æ­¤å¼è®¾ç½®ä¸ºæ°ç»ç´¢å¼(?)

<br>

- è¿å
  - [Boolean](https://docs.microsoft.com/zh-cn/DotNET/api/system.boolean?view=net-6.0)  
    å¦æ `name` åæ°ä¸ `xuid` åæ°ææåçç©å®¶å¨æ­¤ç½ååä¸­åºç°ï¼åä¸º `true`ï¼å¦åä¸º `false`ã
  
<br>