## ðââï¸ ç©å®¶ç»å®æ°æ®

å¨å®éå¼åä¸­ï¼ç»å¸¸æéè¦å°æäºæ°æ®åæå¡å¨ä¸­çæä¸ªç©å®¶ç¸å³èï¼å¹¶å¨æä»¶çå·¥ä½å¨æä¸­ä¸æ­ç»´æ¤è¿äºæ°æ®çéæ±ã  

ä¸ºæ­¤ï¼èæ¬å¼æè®¾è®¡äºç©å®¶ç»å®æ°æ®æ¥å£ãç»å®æ°æ®æ¥å£ä½¿ç¨é® - å¼å¯¹çå½¢å¼å¨å­æ°æ®ã    
å¨ä½ å°æ°æ®ç»å®å°æä¸ªç©å®¶ä¸ä»¥åï¼å³ä½¿å¨ç©å®¶å¯¹è±¡è¶åºä½ç¨åè¢«éæ¯ï¼çè³å½æ­¤ç©å®¶éåºæ¸¸ææ¶ï¼ç©å®¶ç»å®æ°æ®å°ä»ç¶å­å¨ãå½ä½ åæ¬¡è·å¾è¿ä¸ªç©å®¶çç©å®¶å¯¹è±¡çæ¶åï¼ä»ç¶å¯ä»¥è¯»åå°ä¹åå¨å­çç»å®æ°æ®ã  
åªæå½æå¡ç«¯å³é­çæ¶åï¼ææçæ°æ®æä¼è¢«ç»ä¸éæ¯ã

ç±æ­¤ï¼èæ¬å¼æç»äºå¼åèå¨æä»¶çæ´ä¸ªçå½å¨æä¸­è·è¸ªæä¸ªç¹å®ç©å®¶ç¸å³æ°æ®çè½åã  

<br>

å¯¹äºæä¸ªç¹å®çç©å®¶å¯¹è±¡`pl`ï¼æå¦ä¸è¿äºæ¥å£ï¼

#### å¨å­ç©å®¶ç»å®æ°æ®

`pl.setExtraData(name,data)`

- åæ°ï¼
  - name : `String`  
    è¦å¨å­å°ç»å®æ°æ®çåå­
  - data : `ä»»æç±»å`  
    ä½ è¦å¨å­çç»å®æ°æ®ï¼å¯ä»¥æ¯`Null`

- è¿åå¼ï¼æ¯å¦æåå¨å­
- è¿åå¼ç±»åï¼`Boolean` 

<br>

#### è·åç©å®¶ç»å®æ°æ®

`pl.getExtraData(name)`

- åæ°ï¼
  - name : `String`  
    è¦è¯»åçç»å®æ°æ®çåå­
- è¿åå¼ï¼å¨å­çç»å®æ°æ®
- è¿åå¼ç±»åï¼`ä»»æç±»å`ï¼åå³äºå¨å­çæ°æ®ç±»å
  -  å¦è¿åå¼ä¸º `Null` åè¡¨ç¤ºæªè·åå°æå®çç»å®æ°æ®ï¼æèæ°æ®ä¸ºç©º

<br>

#### å é¤ç©å®¶ç»å®æ°æ®

`pl.delExtraData(name)`

- åæ°ï¼
  - name : `String`  
    è¦å é¤çç»å®æ°æ®çåå­
- è¿åå¼ï¼æ¯å¦å é¤æå
- è¿åå¼ç±»åï¼`Boolean`

<br>

## ð¨âð» XUID æ°æ®åº

XUIDæ°æ®åºè®©ä½ å¯ä»¥å³ä½¿å¨ç©å®¶ç¦»çº¿çæ¶åï¼ä¹å¯ä»¥æ¥è¯¢ç©å®¶åå­ä¸XUIDçå¯¹åºå³ç³»ã  
å½ä¸ä¸ªç©å®¶ç¬¬ä¸æ¬¡è¿æçæ¶åï¼ä»çåå­åXUIDå°±ä¼è¢«èªå¨è®°å½å¨åç½® XUID æ°æ®åºä¸­ãä½¿ç¨ä¸é¢çå½æ°æ¥è¿è¡ç¸å³æ¥è¯¢

#### æ ¹æ®ç©å®¶åæ¥è¯¢XUID

`data.name2xuid(name)`

- åæ°ï¼
  - name : `String`  
    è¦æ¥è¯¢çç©å®¶å
- è¿åå¼ï¼ç©å®¶çXUID
- è¿åå¼ç±»åï¼`String`
  - å¦æè¿åå¼ä¸º`Null`ï¼åä»£è¡¨æ¥è¯¢å¤±è´¥

<br>

#### æ ¹æ®XUIDæ¥è¯¢ç©å®¶å

`data.xuid2name(xuid)`

- åæ°ï¼
  - xuid: `String`  
    è¦æ¥è¯¢çç©å®¶XUID
- è¿åå¼ï¼ç©å®¶å
- è¿åå¼ç±»åï¼`String`
  - å¦æè¿åå¼ä¸º`Null`ï¼åä»£è¡¨æ¥è¯¢å¤±è´¥

<br>

#### æ ¹æ®ç©å®¶åæ¥è¯¢UUID

`data.name2uuid(name)`

- åæ°ï¼
  - name : `String`  
    è¦æ¥è¯¢çç©å®¶å
- è¿åå¼ï¼ç©å®¶çUUID
- è¿åå¼ç±»åï¼`String`
  - å¦æè¿åå¼ä¸º`Null`ï¼åä»£è¡¨æ¥è¯¢å¤±è´¥

<br>

#### æ ¹æ®XUIDæ¥è¯¢ç©å®¶UUID

`data.xuid2uuid(xuid)`

- åæ°ï¼
  - xuid: `String`  
    è¦æ¥è¯¢çç©å®¶XUID
- è¿åå¼ï¼ç©å®¶çUUID
- è¿åå¼ç±»åï¼`String`
  - å¦æè¿åå¼ä¸º`Null`ï¼åä»£è¡¨æ¥è¯¢å¤±è´¥

<br>

#### è·åææçç©å®¶ä¿¡æ¯

`data.getAllPlayerInfo()`

- è¿åå¼: ææçç©å®¶ä¿¡æ¯
- è¿åå¼ç±»å: `Array<Object>`
  - æ¯ä¸ªå¯¹è±¡é½å«æä»¥ä¸å±æ§:
    - `name`: ç©å®¶å
    - `xuid`: ç©å®¶XUID
    - `uuid`: ç©å®¶UUID

<br>

æç¤ºï¼XUIDæ°æ®åºä¸­å¨å­çç©å®¶åä¸ºç©å®¶å¯¹è±¡å¯¹åºç`realName`å­æ®µ
