# 使用说明
lua 脚本

把他们放在TBC 的根目录下,注意检查编码是否是ANSI

注意：
1. 自动邮寄会邮寄除了在主背包中的东西的所有东西，所以把要留下的东西放主备包
2. 鞋子必须附魔移动速度

统一要求： 
1. 70级fs,技能全，背包全，
2. 副本脚本都用副本模式 在副本门口(外面)开启，野外打怪，自动打本都用循环模式开启
3. 开始前，修好装备，清空背包

怒焰(最低使用版本要求:1.1.5)：
没有要求

影牙(最低使用版本要求:1.1.5)：
1. 炉石在瑟伯切尔
2. 要求下载dejunk插件，网易有爱自带 并将这段字符串导入进去
~~~
^1^T^Sdestroy^T^SautoOpen^T^Senabled^B^Svalue^N0^t^SbyType^T^SexcessSoulShards^T^Senabled^b^Svalue^N3^t^SpetsAlreadyCollected^b^StoysAlreadyCollected^b^SitemLevelRange^T^Smax^N1^Smin^N1^Senabled^b^t^t^Signore^T^Smiscellaneous^B^Scosmetic^b^Sglyphs^B^Stradeable^B^SequipmentSets^B^Srecipes^b^Sgems^B^SbindsWhenEquipped^b^Sconsumables^B^Sreadable^B^Ssoulbound^b^SitemEnhancements^B^StradeGoods^B^SquestItems^B^SbattlePets^B^Sreagents^B^t^SautoStart^T^Senabled^b^Svalue^N0^t^Sexclusions^T^t^SbelowPrice^T^Senabled^B^Svalue^N5000^t^SbyQuality^T^Spoor^B^Sepic^b^Scommon^b^Suncommon^B^Srare^B^t^Sinclusions^T^S3385^B^S4606^B^S1210^B^S5635^B^S1205^B^S5254^B^S1712^B^S12223^B^S1015^B^S3012^B^S929^B^S9788^B^S3770^B^S3301^B^S9779^B^t^t^Ssell^T^Sauto^B^Sexclusions^T^t^SbyQuality^T^Spoor^B^Sepic^b^Scommon^b^Suncommon^b^Srare^b^t^Sinclusions^T^S25429^B^S25431^B^S8766^B^S8952^B^S17058^B^S27858^B^S17057^B^S24477^B^t^SautoOpen^b^Signore^T^Stradeable^B^Scosmetic^B^Sglyphs^B^Srecipes^B^SequipmentSets^B^Sgems^B^SbindsWhenEquipped^B^Smiscellaneous^B^Sconsumables^B^Sreadable^B^Ssoulbound^B^SitemEnhancements^B^StradeGoods^B^SquestItems^B^SbattlePets^B^Sreagents^B^t^SbelowPrice^T^Senabled^b^Svalue^N2^t^SsafeMode^b^SbyType^T^Sunsuitable^b^SitemLevelRange^T^Smax^N1^Smin^N1^Senabled^b^t^t^t^Sversion^N3^Sgeneral^T^SuseGuildRepair^B^SautoRepair^b^Schat^T^Sdestroy^B^Sframe^SChatFrame1^Senabled^B^Ssell^B^Sverbose^b^Sreason^b^t^t^t^^
~~~

血色(最低使用版本要求:1.1.6)：
1. 炉石在布瑞尔
2. 点出气定神闲天赋

MLD(最低使用版本要求:1.1.6):
1. 炉石在葬影村
2. 点出气定神闲天赋
3. 100左右自然抗性装备或者自带自然防护药剂
4. 自带灵纹布绷带,灵纹布绷带,灵纹布绷带
5. 要求下载dejunk插件，网易有爱自带 并将这段字符串导入进去
~~~
^1^T^Sdestroy^T^SautoOpen^T^Senabled^B^Svalue^N0^t^SbyType^T^SexcessSoulShards^T^Senabled^b^Svalue^N3^t^SpetsAlreadyCollected^b^StoysAlreadyCollected^b^SitemLevelRange^T^Smax^N1^Smin^N1^Senabled^b^t^t^Signore^T^Srecipes^b^Scosmetic^B^Sglyphs^B^Smiscellaneous^B^SequipmentSets^B^Sgems^b^Stradeable^B^SbindsWhenEquipped^b^Sconsumables^B^Sreadable^B^Ssoulbound^b^SitemEnhancements^B^StradeGoods^B^SquestItems^B^SbattlePets^B^Sreagents^B^t^SautoStart^T^Senabled^b^Svalue^N0^t^Sexclusions^T^t^SbelowPrice^T^Senabled^B^Svalue^N4055^t^SbyQuality^T^Spoor^B^Sepic^b^Scommon^b^Suncommon^b^Srare^b^t^Sinclusions^T^S4625^B^S1645^B^S5635^B^S4422^B^S6149^B^S20763^B^S9779^B^S2453^B^S8836^B^S5254^B^S3936^B^S4599^B^S3928^B^S3770^B^S10286^B^S2452^B^S3385^B^S8831^B^S1210^B^S3818^B^S1710^B^S4637^B^S3358^B^S3938^B^S1712^B^S2450^B^S1015^B^S2447^B^S1205^B^S3671^B^S4421^B^S10312^B^S4419^B^S4608^B^S785^B^S12223^B^S20976^B^S3819^B^S3357^B^S765^B^S1707^B^S3676^B^S3012^B^S929^B^S4606^B^S8029^B^S3301^B^S9788^B^t^t^Ssell^T^Sauto^B^Sexclusions^T^t^SbyQuality^T^Spoor^B^Sepic^b^Scommon^b^Suncommon^b^Srare^b^t^Sinclusions^T^S25429^B^S24477^B^S8766^B^S8952^B^S17058^B^S17057^B^S25431^B^S27858^B^t^SautoOpen^b^Signore^T^Stradeable^B^Scosmetic^B^Sglyphs^B^Srecipes^B^SequipmentSets^B^Sgems^B^SbindsWhenEquipped^B^Smiscellaneous^B^Sconsumables^B^Sreadable^B^Ssoulbound^B^SitemEnhancements^B^StradeGoods^B^SquestItems^B^SbattlePets^B^Sreagents^B^t^SbelowPrice^T^Senabled^b^Svalue^N2^t^SsafeMode^b^SbyType^T^Sunsuitable^b^SitemLevelRange^T^Smax^N1^Smin^N1^Senabled^b^t^t^t^Sversion^N3^Sgeneral^T^SuseGuildRepair^B^SautoRepair^b^Schat^T^Sdestroy^B^Sframe^SChatFrame1^Senabled^B^Ssell^B^Sverbose^b^Sreason^b^t^t^t^^
~~~


decompose(自动分解)(谨慎使用)(最低使用版本要求:1.1.6)

1.事先整理好背包，确保没有重要物品

2.全部在除了主背包之外的物品都将尝试被分解

3.只在背包中留下要分解的装备,不要留别的东西，不然会浪费时间





使用tip:

1. 不会使用技能，不开门。
解决： 右键打开方式，记事本，另存为，下方的编码设置为ANSI
2. 乱跑
解决：确保你下载最新的脚本wow-lua
3. mld被小怪射死
解决：自然抗性装备和自然防护药水备上

