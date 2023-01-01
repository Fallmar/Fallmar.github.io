---
export_on_save:
  html: true
---
[< 返回](../notice_index.html "返回至上一页")

>本页面为试验稿，正文内容尚未完工

# NBT附魔
语法：

>give <目标选择器> minecraft:物品id{NBT标签1,NBT标签2}

分节符：`§`

## NBT

1. **Enchantments** 使用命令施加的魔咒，可以忽略魔咒之间的冲突和等级限制。
子标签：`id` `lvl`
必须有的子标签：**所有**
格式：Enchantments:[{id:"魔咒ID",lvl:#魔咒等级},{id:"魔咒ID",lvl:#魔咒等级}...(以此类推)]
示例：Enchantments:[{id:"minecraft:sharpness",lvl:6},{id:"minecraft:unbreaking",lvl:2}]

2. **display** 控制物品的自定义显示信息（名称、描述、皮革盔甲的颜色等等）。
子标签：`Name` `color` `lore`
必须有的子标签：**至少一个**
格式：display:{Name:"物品名称的JSON文本",color:"颜色代码",Lore:["第一行","第二行（如此类推）"]}
示例：display:{Name:'["极好的剑"]'}

3. **Unbreakable** 其值＞0时，工具的耐久度不会下降(无法损坏)。
示例：Unbreakable:1b

## 魔咒ID列表
水下速掘：aqua_affinity
节肢杀手：bane_of_arthropods
爆炸保护：blast_protection
引雷：channeling
绑定诅咒：binding_curse
消失诅咒：vanishing_curse
深海探索者：depth_strider
效率：efficiency
摔落保护：feather_falling
火焰附加：fire_aspect
火焰保护：fire_protection
火矢：flame
时运：fortune
冰霜行者：frost_walker
穿刺：impaling
无限：infinity
击退：knockback
抢夺：looting
忠诚：loyalty
海之眷顾：luck_of_the_sea
饵钓：lure
经验修补：mending
多重射击：multishot
穿透：piercing
力量：power
弹射物保护：projectile_protection
保护：protection
冲击：punch
快速装填：quick_charge
水下呼吸：respiration
激流：riptide
锋利：sharpness
精准采集：silk_touch
亡灵杀手：smite
灵魂疾行：soul_speed
横扫之刃：sweeping	
荆棘：thorns
耐久：efficiency

@import "../../copy_right.md"