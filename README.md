# 四叶草拼音输入方案

由于原项目已经很久没有更新了，故fork下来，只是自用，随缘维护。    

## 与原项目的不同

- 加入小鹤双拼方案，将`default.custom.yaml`文件中的`clover`改成`clover-flypy`，重新部署即可使用；    
- 使用[pypinyin-dict](https://github.com/mozillazg/pypinyin-dict)导入`cc_cedict`的数据，~~（可能）提高了词库拼音的准确率；~~   经测试发现，`cc_cedit`数据错误还是太多，pypinyin开源项目本身的缺陷，无能为力，还是推荐自行导入搜狗词库，至少可以保证日常用词的准确性；    
- 使用[pypinyin-dict](https://github.com/mozillazg/pypinyin-dict)导入`地`字的词组；    
- fork了[rime-symbols](https://github.com/so1ar/rime-symbols)，并修复了与新版opencc不兼容的问题；    
- 构建时使用词库的最新版本。    

## 安装使用

和原项目相同，在[releases](https://github.com/so1ar/rime-cloverpinyin/releases)页面下载压缩包，参照原项目的教程安装即可；    

Arch以及衍生版用户可以从aur安装[rime-solarpinyin](https://aur.archlinux.org/packages/rime-solarpinyin)。    
