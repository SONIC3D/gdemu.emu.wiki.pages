---
layout: post
title:  "各种土星主板对应的ODE(光驱模拟板)类型"
author: "SONIC3D"
date:   2017-07-18 01:21:00 +0800
categories: rhea saturn
---
### 土星的ODE(Optical Drive Emulator/光驱模拟板)的类型

* 实物外观图片参考

    | Rhea：适用于光驱排线为20芯的机型 | Phoebe：适用于光驱排线为21芯的机型 |
    |-------|-------|
    | [![T_RHEA_IMG]][RHEA_IMG] | [![T_PHOEBE_IMG]][PHOEBE_IMG] |

### 土星的主板版本类型
注：以下主板图片出处为[<セガサターン　本体の種類(2)>](https://www9.atwiki.jp/nannansei/pages/15.html){:target="_blank"}

1. [VA 0] / [VA 0.5] / [VA 1]，对应Rhea

    这类主板的机型都是双灯的，听上去似乎很好鉴别，但实际上双灯机型不一定都是使用Rhea的，因为有VA2主板的双灯机型存在。

    | VA 0 | VA 0.5 | VA 1 |
    |-------|-------|-------|
    | [![T VA 0]][VA 0] | [![T VA 0.5]][VA 0.5] | [![T VA 1]][VA 1] |

2. VA SG([VA 2] / [VA 4]) / VA SD([VA 3] / [VA 5])，对应Phoebe，且跳线置于Type 2位置

    这两类主板中VA2和VA4几乎一样，VA3和VA5也几乎一样，只有通过少量芯片的不同和手柄板是否双灯来鉴别。

    | VA 2 | VA 3 | VA 4 | VA 5 |
    |-------|-------|-------|-------|
    | [![T VA 2]][VA 2] | [![T VA 3]][VA 3] | [![T VA 4]][VA 4] | [![T VA 5]][VA 5] |

3. [VA 6] / [VA 7] / [VA 8] / [VA 9]，对应Phoebe，且跳线置于Type 3位置

    这4类主板可以通过拆机后，拿起光驱，从光驱下方的散热孔里看到主板中间Made in Japan上方的印刷文字来确定版本。

    | VA 6 | VA 7 | VA 8 | VA 9 |
    |-------|-------|-------|-------|
    | [![T VA 6]][VA 6] | [![T VA 7]][VA 7] | [![T VA 8]][VA 8] | [![T VA 9]][VA 9] |

4. [VA 10] / [VA 11] / [VA 13] / [VA 15]，对应Phoebe，且跳线置于Type 4位置

    这4类主板可以通过拆机后，拿起光驱，从光驱下方的散热孔里看到主板中间Made in Japan上方的印刷文字来确定版本。
    
    | VA 10 | VA 11 | VA 13 | VA 15 |
    |-------|-------|-------|-------|
    | [![T VA 10]][VA 10] | [![T VA 11]][VA 11] | [![T VA 13]][VA 13] | [![T VA 15]][VA 15] |
    | 有硬件Bug，见备注 | 有硬件Bug，见备注 |  |  |

    备注：VA10和VA11有68000音频控制器方面的设计Bug，导致Outrun和太空哈利的Rev 00版不能运行，但是这两个游戏有Rev 01版可以在这两种主板上正常运作。

### Rhea和Phoebe的购买

* GDEmu作者网站在这里[https://gdemu.wordpress.com][gdemu-homepage]{:target="_blank"}，可以自己去联系作者预定，本人暂无暇进行任何代购事宜的运作。

[RHEA_IMG]:     {{ site.url }}/assets/posts_img/20170718/rhea_front.jpg
[PHOEBE_IMG]:   {{ site.url }}/assets/posts_img/20170718/phoebe_front.jpg
[T_RHEA_IMG]:   {{ site.url }}/assets/posts_img/20170718/thumb_rhea_front.jpg
[T_PHOEBE_IMG]: {{ site.url }}/assets/posts_img/20170718/thumb_phoebe_front.jpg

[VA 0]:     {{ site.url }}/assets/posts_img/20170718/VA0_FRONT_01a3.jpg
[VA 0.5]:   {{ site.url }}/assets/posts_img/20170718/VA0.5_SS_FRONT.jpg
[VA 1]:     {{ site.url }}/assets/posts_img/20170718/VA1_F_01S.jpg
[VA 2]:     {{ site.url }}/assets/posts_img/20170718/VA2_SG_F_01S.jpg
[VA 3]:     {{ site.url }}/assets/posts_img/20170718/VA3_SD_171-7130B_F_01S2.jpg
[VA 4]:     {{ site.url }}/assets/posts_img/20170718/VA4_F_01_S.jpg
[VA 5]:     {{ site.url }}/assets/posts_img/20170718/VA5_SD_171-7130C_F_01S.jpg
[VA 6]:     {{ site.url }}/assets/posts_img/20170718/VA6_SG_01S.jpg
[VA 7]:     {{ site.url }}/assets/posts_img/20170718/VA7_SD_FRONT_01.jpg
[VA 8]:     {{ site.url }}/assets/posts_img/20170718/VA8x.jpg
[VA 9]:     {{ site.url }}/assets/posts_img/20170718/VA9x.jpg
[VA 10]:    {{ site.url }}/assets/posts_img/20170718/VA10x.jpg
[VA 11]:    {{ site.url }}/assets/posts_img/20170718/VA11_171-7288B_F_01S.jpg
[VA 13]:    {{ site.url }}/assets/posts_img/20170718/VA13_FRONT_01S.jpg
[VA 15]:    {{ site.url }}/assets/posts_img/20170718/VA15_171-7462B_F_01S.jpg

[T VA 0]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA00.jpg
[T VA 0.5]: {{ site.url }}/assets/posts_img/20170718/thumbs_VA05.jpg
[T VA 1]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA1.jpg
[T VA 2]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA2.jpg
[T VA 3]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA3.jpg
[T VA 4]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA4.jpg
[T VA 5]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA5.jpg
[T VA 6]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA6.jpg
[T VA 7]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA7.jpg
[T VA 8]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA8.jpg
[T VA 9]:   {{ site.url }}/assets/posts_img/20170718/thumbs_VA9.jpg
[T VA 10]:  {{ site.url }}/assets/posts_img/20170718/thumbs_VA10.jpg
[T VA 11]:  {{ site.url }}/assets/posts_img/20170718/thumbs_VA11.jpg
[T VA 13]:  {{ site.url }}/assets/posts_img/20170718/thumbs_VA13.jpg
[T VA 15]:  {{ site.url }}/assets/posts_img/20170718/thumbs_VA15.jpg

[gdemu-homepage]: https://gdemu.wordpress.com
