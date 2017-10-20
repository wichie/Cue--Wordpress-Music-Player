
 * Cue中文修改版
 *
 * @package Cue
 * @author Brady Vercher
 * @copyright Copyright (c) 2014, AudioTheme, LLC
 * @license GPL-2.0+
 *
 * @wordpress-plugin
 * Plugin Name: Cue中文修改版
 * Plugin URI: http://www.wichie.com
 * Description: 创建漂亮的，完全响应的音频播放列表。
 * Version: 9.9.9
 * Author: Wichie，zhw-island,Audio theme
 * Author URI: http://www.wichie.com
 * License: GPL-2.0+
 * License URI: https://www.gnu.org/licenses/gpl-2.0.html
 * Text Domain: Cue中文修改版
 * Domain Path: /languages

 
 使用方法：
 只需要什么设置一下，先把下面代码放到你的页面底部，再把把下面的数字10改为你的歌单的对应ID即可。
还有一步，就是引入font awesome字体图标，否则会不出现一些图标。
 
 
 *------------------代码如下-------------------------
 
     <?php if (function_exists('cue_playlist') ) {?>
	<?php cue_playlist(10); ?>
    <?php }?>
 
 *--------------------------------------------------
 
 
预览网址：http://www.wichie.com
