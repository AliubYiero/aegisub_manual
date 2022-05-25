# unanimated's Aegisub Scripts Manuals

unanimated的Aegisub自动化插件中文手册(by Yiero). 

挺有意思的一组Aegisub脚本, 您可以通过 [[unanimated/luaegisub](https://github.com/unanimated/luaegisub)] 访问他的Github Aegisub插件库和他自己编写的英文手册.

> 我有点怀疑他做了一整套的特效标签可视化出来. 

---

| 插件                                                         | 简介                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Cycles](./docs/Cycles.md)                                   | 快速应用 `blur`/`bord`/`shad`/`an`/`alpha`/`fsp` 等标签.     |
| [*iBus](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#ibus) | 快速应用 斜体/粗体/下划线/删除线                             |
| [*Line Breaker](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#linebreak) | 识别行内需要换行的位置, 并插入换行符                         |
| [*Join /](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#join) [*Split /](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#split) [*Snap](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#snap) | 连接行 / 分割行 / 关键帧定位行                               |
| [*Jump to Next](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#next) | Go to the line that comes after all the lines of your current multi-line "sign" (mocha, gradient, etc.) |
| [*Re-Split](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#resplit) / [*Reverse](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#reverse) | 移动行内字符顺序                                             |
| [*Aladin's Lamp](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#aladin) | Solve some problems with right-to-left text when typesetting in Arabic |
| [*Script Cleanup](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#cleanup) | 删除文本中不需要的标签以及其它东西                           |
| [*Blur and Glow](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#blurglow) | 制作边缘模糊 / 制作一个"发光"效果                            |
| [*HYDRA](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#hydra) | 快速添加标签(支持多行同时操作)                               |
| [*Hyperdimensional Relocator](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#relocator) | 做各种各样的事情, 主要涉及pos, move, org, clip, rotations和标记。 |
| [*Recalculator](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#recalculator) | 通过乘法或加法运算重新赋值标签的参数                         |
| [*Colourise](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#colourise) | 快速操作颜色 / 渐变颜色                                      |
| [*Multi-Line Editor](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#multiedit) | 类似记事本一样编辑多行文本                                   |
| [*MultiCopy](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#multicopy) | 从选中行中复制特定文本 / 粘贴特定文本到选中行                |
| [*FadeWorkS](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#fade) | 创建一个普通的渐入渐出, 甚至更复杂的渐入渐出效果             |
| [*Selectricks](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#selectrix) | 根据给定的标准选择或排序行(类似于选择多行)                   |
| [*ShiftCut](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#shiftcut) | Timing operations                                            |
| [*Time Signs](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#timesigns) | Time signs from timecodes like this one: {TS 5:36}           |
| [*Change Case](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#capitalise) | 改变文本的大小写                                             |
| [*Significance](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#import) | Do a shitload of things that the other scripts don't do      |
| [*Activ8 /](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#activ8) [*ModiFire](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#modifire) | 简化复杂文本 / 修改现有标签                                  |
| [*Masquerade](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#masquerade) | save/load masks; shift tags in line; apply \an or \q2 tags; alpha time signs; make various replacements |
| [*NecrosCopy](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#necroscopy) | clip2fax; clip2frz; copy things from one line to others; split line into parts |
| [*Encode - Hardsub](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#enchsub) | 压制文件(通过x264) \| 这里我推荐使用domo的[[Encode - Hardsub](https://github.com/qwe7989199/aegisub_scripts/releases/tag/v1.3)]压制插件 |
| [*Multiplexer](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#mux) | 混流/封装视频(通过mkvmerge)                                  |
| [*Runemap](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#runemap) | 显示平假名/片假名与对应的罗马字的列表                        |
| [*Backup Checker](http://unanimated.hostfree.pw/ts/scripts-manuals.htm#backup) | 备份文件, 使您能在编辑文本后再回看未编辑行检查               |

> 持续更新中, 若未写完的插件说明(带有*)将会跳转至unanimated自己的英文手册界面.

> 如果[简介]是英文的, 说明我看不懂他的简要直接的把他的简要拉了下来. 我写到对应的插件的说明才会更新对应的简要.

> 只能说, 啊, 功能炒鸡丰富呢.

> [[comment](./comment)]中有本人对这些lua脚本一些注解, 正因如此, 并不会很快的书写手册.

---

