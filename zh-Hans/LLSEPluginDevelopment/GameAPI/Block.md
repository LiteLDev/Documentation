## ð¦ æ¹åå¯¹è±¡ API

å¨èæ¬å¼æä¸­ï¼ä½¿ç¨ãæ¹åå¯¹è±¡ãæ¥æä½åè·åæä¸ç±»æ¹åçç¸å³ä¿¡æ¯ã

### è·åä¸ä¸ªæ¹åå¯¹è±¡

#### ä»äºä»¶æAPIè·å

éè¿æ³¨å**äºä»¶çå¬**å½æ°ï¼æèè°ç¨æäº**è¿åæ¹åå¯¹è±¡**çå½æ°ï¼è·åå°BDSç»åºçä¸ç¸å³äºä»¶æå³çæ¹åå¯¹è±¡  
è¯¦è§ [äºä»¶çå¬ææ¡£ - EventAPI](LLSEPluginDevelopment/EventAPI/Listen.md)  

#### éè¿æ¹ååæ è·å

éè¿æ­¤å½æ°æ¥æå¨çæå¯¹è±¡ï¼æ³¨æï¼ä½ è¦è·åçæ¹åå¿é¡»å¤äºå·²è¢«å è½½çèå´ä¸­ï¼å¦åä¼åºç°é®é¢

`mc.getBlock(pos)`  
`mc.getBlock(x,y,z,dimid)`

- åæ°ï¼
  - pos : `IntPos `  
    æ¹åæå¨åæ ï¼æèä½¿ç¨x, y, z, dimidæ¥ç¡®å®æ¹åä½ç½®ï¼
- è¿åå¼ï¼çæçæ¹åå¯¹è±¡ 
- è¿åå¼ç±»åï¼`Block`
  - å¦è¿åå¼ä¸º `Null` åè¡¨ç¤ºè·åæ¹åå¤±è´¥

> æ³¨æï¼ä¸è¦**é¿æä¿å­**ä¸ä¸ªæ¹åå¯¹è±¡  
> å½æ¹åå¯¹è±¡å¯¹åºçæ¹åè¢«éæ¯æ¶ï¼å¯¹åºçæ¹åå¯¹è±¡å°åæ¶éæ¾ãå æ­¤ï¼å¦ææé¿ææä½æä¸ªæ¹åçéè¦ï¼è¯·éè¿ä¸è¿°éå¾è·åå®æ¶çæ¹åå¯¹è±¡

<br>


### æ¹åå¯¹è±¡ - å±æ§

æ¯ä¸ä¸ªæ¹åå¯¹è±¡é½åå«ä¸äºåºå®çå¯¹è±¡å±æ§ãå¯¹äºæä¸ªç¹å®çæ¹åå¯¹è±¡`bl`ï¼æä»¥ä¸è¿äºå±æ§

| å±æ§                    | å«ä¹                 | ç±»å      |
| ----------------------- | -------------------- | --------- |
| bl.name                 | æ¸¸æåæ¾ç¤ºçæ¹ååç§° | `String`  |
| bl.type                 | æ¹åæ åç±»åå       | `String`  |
| bl.id                   | æ¹åçæ¸¸æåid       | `Integer` |
| bl.pos                  | æ¹åæå¨åæ          | `IntPos`  |
| bl.tileData             | æ¹åæ°æ®å¼           | `Integer` |
| bl.variant              | The block variant    | `Integer` |
| bl.translucency         | æ¹åéæåº¦           | `Integer` |
| bl.thickness            | æ¹åååº¦             | `Integer` |
| bl.isAir                | æ¹åæ¯å¦ä¸ºç©ºæ°       | `Boolean` |
| bl.isBounceBlock        | æ¯å¦ä¸ºå¯å¼¹è·³æ¹å     | `Boolean` |
| bl.isButtonBlock        | æ¯å¦ä¸ºæé®æ¹å       | `Boolean` |
| bl.isCropBlock          | æ¯å¦ä¸ºåä½ç©æ¹å     | `Boolean` |
| bl.isDoorBlock          | æ¯å¦ä¸ºé¨æ¹å         | `Boolean` |
| bl.isFenceBlock         | æ¯å¦ä¸ºæ æ æ¹å       | `Boolean` |
| bl.isFenceGateBlock     | æ¯å¦ä¸ºæ æ é¨æ¹å     | `Boolean` |
| bl.isThinFenceBlock     | æ¯å¦ä¸ºç»æ æ æ¹å     | `Boolean` |
| bl.isHeavyBlock         | æ¯å¦ä¸ºéçæ¹å       | `Boolean` |
| bl.isStemBlock          | æ¯å¦ä¸ºå¹²æ¹å         | `Boolean` |
| bl.isSlabBlock          | æ¯å¦ä¸ºåè½¬æ¹å       | `Boolean` |
| bl.isUnbreakable        | æ¹åæ¯å¦ä¸ºä¸å¯ç ´å   | `Boolean` |
| bl.isWaterBlockingBlock | æ¹åæ¯å¦å¯é»æ¡æ°´     | `Boolean` |

è¿äºå¯¹è±¡å±æ§é½æ¯åªè¯»çï¼æ æ³è¢«ä¿®æ¹

<br>

### æ¹åå¯¹è±¡ - å½æ°

æ¯ä¸ä¸ªæ¹åå¯¹è±¡é½åå«ä¸äºå¯ä»¥æ§è¡çæåå½æ°ï¼æåæ¹æ³ï¼ãå¯¹äºæä¸ªç¹å®çæ¹åå¯¹è±¡`bl`ï¼å¯ä»¥éè¿ä»¥ä¸è¿äºå½æ°å¯¹è¿ä¸ªæ¹åè¿è¡ä¸äºæä½

#### ç ´åæ¹å

`bl.destroy(drop)`

- åæ°ï¼
  - drop : `Boolen`  
    æ¯å¦çææè½ç©
- è¿åå¼ï¼æ¯å¦æåç ´å
- è¿åå¼ç±»åï¼`Boolen`

<br>

#### è·åæ¹åå¯¹åºçNBTå¯¹è±¡

`bl.getNbt()`

- è¿åå¼ï¼æ¹åçNBTå¯¹è±¡
- è¿åå¼ç±»åï¼`NbtCompound`

<br>

#### åå¥æ¹åå¯¹åºçNBTå¯¹è±¡

`bl.setNbt(nbt)`

- åæ°ï¼
  - nbt : `NbtCompound`  
    NBTå¯¹è±¡
- è¿åå¼ï¼æ¯å¦æååå¥
- è¿åå¼ç±»åï¼`Boolean`

å³äºNBTå¯¹è±¡çæ´å¤ä½¿ç¨ï¼è¯·åè [NBTæ¥å£ææ¡£](LLSEPluginDevelopment/NbtAPI/NBT.md)
æ³¨æï¼æéä½¿ç¨æ­¤apiï¼è¯·èèä½¿ç¨ `mc.setBlock()` ä»£æ¿

<br>

#### è·åæ¹åçBlockState

`bl.getBlockState()`

- è¿åå¼ï¼æ¹åç`BlockState`
- è¿åå¼ç±»åï¼`Object`

æ¹ä¾¿å½æ°ï¼åå©è§£ææ¹å`BlockState`å¹¶è½¬æ¢ä¸º`Object`ï¼æ¹ä¾¿è¯»åä¸è§£æ  
ç­ä»·äºèæ¬æ§è¡`block.getNbt().getTag("states").toObject()`

<br>

#### å¤æ­æ¹åæ¯å¦æ¥æå®¹å¨

`bl.hasContainer()`

- è¿åå¼ï¼è¿ä¸ªæ¹åæ¯å¦æ¥æå®¹å¨
- è¿åå¼ç±»åï¼`Boolean`

å¦ç®±å­ãæ¡¶ç­å®¹å¨ï¼ä»ä»¬åèªæ¥æä¸ä¸ªå±äºèªå·±çå®¹å¨å¯¹è±¡

<br>

#### è·åæ¹åææ¥æçå®¹å¨å¯¹è±¡

`bl.getContainer()`

- è¿åå¼ï¼è¿ä¸ªæ¹åææ¥æçå®¹å¨å¯¹è±¡
- è¿åå¼ç±»åï¼`Container`

å³äºå®¹å¨å¯¹è±¡çæ´å¤ä½¿ç¨ï¼è¯·åè [å®¹å¨å¯¹è±¡ APIææ¡£](LLSEPluginDevelopment/GameAPI/Container.md)

<br>

#### å¤æ­æ¹åæ¯å¦æ¥ææ¹åå®ä½

`bl.hasBlockEntity()`

- è¿åå¼ï¼è¿ä¸ªæ¹åæ¯å¦æ¥ææ¹åå®ä½
- è¿åå¼ç±»åï¼`Boolean`

<br>

#### è·åæ¹åææ¥æçæ¹åå®ä½

`bl.getBlockEntity()`

- è¿åå¼ï¼è¿ä¸ªæ¹åææ¥æçæ¹åå®ä½
- è¿åå¼ç±»åï¼`BlockEntity`

<br>

#### å é¤æ¹åææ¥æçæ¹åå®ä½

`bl.removeBlockEntity()`

- è¿åå¼ï¼æ¯å¦æåå é¤
- è¿åå¼ç±»åï¼`Boolean`

å³äºæ¹åå®ä½å¯¹è±¡çæ´å¤ä½¿ç¨ï¼è¯·åè [æ¹åå®ä½å¯¹è±¡ APIææ¡£](LLSEPluginDevelopment/GameAPI/BlockEntity.md)

<br>

### å¶ä»æ¹åå½æ° API

ä¸é¢è¿äºAPIæä¾äºä¸æ¸¸æä¸­æå®ä½ç½®æ¹åäºå¨çAPI

#### è®¾ç½®æå®ä½ç½®çæ¹å

`mc.setBlock(pos,block,tiledata)`  
`mc.setBlock(x,y,z,dimid,block,tiledata)`

- åæ°ï¼
  - pos : `IntPos`  
    ç®æ æ¹åä½ç½®ï¼æèä½¿ç¨x, y, z, dimidæ¥ç¡®å®æ¹åä½ç½®ï¼
  - block : `Block` ã`String` æ `NBTCompound`
    è¦è®¾ç½®æçæ¹åå¯¹è±¡ãæ¹åæ åç±»ååï¼å¦`minecraft:stone`ï¼ææ¹åNBTæ°æ®
  - tiledata : `Integer`  
    æ¹åç¶æå¼ï¼ååç /setBlock æä»¤ç tiledataï¼é»è®¤ä¸º0ï¼ä»éè¿æ¹åç±»ååæ¾ç½®æ¹åæ¶ææ
- è¿åå¼ï¼æ¯å¦æåè®¾ç½®
- è¿åå¼ç±»åï¼`Boolean`

éè¿æ­¤å½æ°ï¼å°ä¸ä¸ªåæ å¯¹åºçæ¹åè®¾ç½®æå¦ä¸ä¸ªï¼ç±»ä¼¼äºå½ä»¤ `/setblock`

<br>

#### å¨æå®ä½ç½®çæç²å­ææ

`mc.spawnParticle(pos,type)`  
`mc.spawnParticle(x,y,z,dimid,type)`

- åæ°ï¼
  - pos : `IntPos` / `FloatPos`  
    ç®æ çæä½ç½®ï¼æèä½¿ç¨x, y, z, dimidæ¥ç¡®å®æ¹åä½ç½®ï¼
  - type : `String`  
    è¦çæçç²å­ææåç§°ï¼å¯æ¥éwikiå¾ç¥ï¼
- è¿åå¼ï¼æ¯å¦æåçæ
- è¿åå¼ç±»åï¼`Boolean`

ç²å­ææåç§°å¯ä»¥æ¥é[Minecraft Wiki](https://minecraft.fandom.com/zh/wiki/%E7%B2%92%E5%AD%90?variant=zh#.E7.B1.BB.E5.9E.8B)å¾ç¥ï¼å¨ä¼ å¥åæ°çæ¶åä¸è¦å¿è®°å½åç©ºé´åç¼ãç±»ä¼¼äº `minecraft:heart_particle`