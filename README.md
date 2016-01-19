# YUIdoc

### how to using yuidoc? ###

基于node, 需要翻墙, 使用简单<br><br>
offical site: http://yui.github.io/yuidoc/<br><br>

## Installation and Usage ##
1. Download and install Node.js
2. Run npm -g install yuidocjs.
3. Run yuidoc . at the top of your JS source tree.


----------



### 需要在项目根目录下配置yuidoc.json ###
yuidoc默认扫描子目录中所有js文件

    {
      "name": "页面标题<title>",
      "description": "YUIDoc documentation tool written in JavaScript",
      "version": "0.9.0",
      "url": "http://yuilibrary.com/projects/yuidoc",
      "logo": "http://pic.c-ctrip.com/common/c_logo2013.png",
      "options": {
          "linkNatives": "true",
          "outdir": "./output"
      }
    }


