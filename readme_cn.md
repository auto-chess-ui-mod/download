<h1 align="center">
   <img src="https://github.com/auto-chess-ui-mod/download/raw/master/images/banner_img_cn.jpg" alt="UI Mod for Dota 2 Auto Chess" title="UI Mod for Dota 2 Auto Chess" />
</h1>
<p align="center">  
 <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
 <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2UKM4JREAPTBG"><img src="https://img.shields.io/badge/buy%20me%20some-candy-yellow.svg"></a>
 
</p>

<p align="center">
  这个 UI MOD 提升了刀塔自走棋的用户体验。 <br> <br>
  <span><strong>源代码: </strong><a href="https://github.com/auto-chess-ui-mod/source ">repository </a></span><br>
  <span><strong>生成器: </strong><a href="https://github.com/auto-chess-ui-mod/generator">repository</a></span>
</p>

## 声明

该项目基于个人兴趣爱好，**如要使用请自行承担风险**。

在我个人看来，这个 MOD 遵循了 Valve 的自定义模组规则（可参见：[这里](https://dota2.gamepedia.com/Ban#Exceptions)）并不会导致封禁。但还是重申下，该风险需要使用者自行承担。

如果自走棋的开发者要我移除下载链接的话，我会满足他们的请求。

**注意：**精简版的代码不涉及抽取概率，所以我觉得应该会更安全。


## 使用说明和下载

你可以遵循以下步骤安装这个 MOD：

1. 下载你需要的版本：
a. [完全版](https://github.com/auto-chess-ui-mod/download/raw/master/vpk/full/pak01_dir.vpk)：*升级金币提示、打野提示、抽取概率*
b. [精简版](https://github.com/auto-chess-ui-mod/download/raw/master/vpk/lite/pak01_dir.vpk)：*升级金币提示、打野提示*
c. [完全版 + 棋子强度评级提示](https://github.com/auto-chess-ui-mod/download/raw/master/vpk/full_tier/pak01_dir.vpk)（强度评级基于 [qihl.gg 强度列表](https://qihl.gg/tierlist)）

2. 找到你的 Dota 2 安装文件夹
   *例如：* `D:\Steam\steamapps\common\dota 2 beta`

3. 在 `game` 文件夹内，新建一个 `custom_dac_ui` 文件夹
   *例如：* `D:\Steam\steamapps\common\dota 2 beta\game\custom_dac_ui`

4. 将你在第 1 步中下载的 `pak01_dir.vpk` 文件拷贝到 `custom_dac_ui` 文件夹内

5. 用文本编辑器打开 `game\dota` 文件夹下的 `gameinfo.gi` 文件

6. 如下图在 `gameinfo.gi` 中添加两行内容

![](https://github.com/auto-chess-ui-mod/download/raw/master/images/modify_gameinfo_cn.jpg)

**请注意两点：**

a. 这两行内容的位置请保持与图中一致

b. Dota 2 升级时也许会重置 `gameinfo.gi`，此时重复上面的第 5、6 步即可。

### 致谢
我在开发这个 MOD 的时候，参考了以下开发者的工作：

`Divine UI Source` [Repo](https://github.com/dota2-divine-ui/divine-ui-source)  

`Dota Auto Chess: Trainer` [网页链接](https://dota2chess.com/)