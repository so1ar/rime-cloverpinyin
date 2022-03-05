# 四叶草拼音输入方案

由于原项目已经很久没有更新了，故fork下来，只是自用，随缘维护。    

## 与原项目的不同

- 加入小鹤双拼方案，将`default.custom.yaml`文件中的`clover`改成`clover-flypy`，重新部署即可使用；    
- 使用[pypinyin-dict]{https://github.com/mozillazg/pypinyin-dict}导入`cc_cedict`的数据，（可能）提高了词库拼音的准确率；    
- 构建时使用词库的最新版本。    

## 已知问题

- 在Archlinux上（其它系统没测试过）[rime-symbols]{https://github.com/fkxxyz/rime-symbols}用不了，这是原项目就存在的问题，不知道有什么解决办法。    

## 安装使用

和原项目相同，在[releases]{https://github.com/so1ar/rime-cloverpinyin/releases}页面下载压缩包，参照原项目的教程安装即可；    

Arch以及衍生版用户可以从aur安装[rime-solarpinyin]{https://aur.archlinux.org/packages/rime-solarpinyin}。    
