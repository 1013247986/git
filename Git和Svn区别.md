## 一、分布式 VS 集中式

- 集中式版本控制系统，其版本库是集中存放在中央服务器上的，当需要的时候可以从中央服务器取得最新的版本，然后修改完毕之后再上传到中央服务器，类比图书馆借书修改的过程，但是其最大的不便之处就是必须要联网。
- 分布式版本控制系统，每个人的电脑上都是一个完整的版本库，所以不需要联网。例如你修改了文件1，你的同事在他的电脑上也修改了文件1，那么你们俩只需要把各自的修改推送给对方，就可以互相看到修改了。实际使用分布式版本控制系统的时候，其通常有一台“中央服务器”，但是这个服务器只是为了方便大家“交换”修改。例如两个人不在同一个局域网，两台电脑互相访问不了，又或者另外一人的电脑没开机等情况。

