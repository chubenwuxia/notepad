# 改进notepad++
1.NoteList中显示条目增加时间显示（显示的时间是最后一次修改时间，每次进行修改时间都会更新）通过Cursor从数据库中读取出最后一次修改的时间：通过SimpleCursorAdapter装填，PROJECTION中定义显示的时间然后在在dataColumns，viewIDs中补充时间部分
![](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(1).png)
2.增加了搜索功能，使用标题关键字搜索list_options_menu.xml，添加一个搜索的item
NoteList中找到onOptionsItemSelected方法，在switch中添加搜索的case语句:在新建的NoteSearch的activity
![](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(2).png)
3.增加了更改记事本背景的功能有五种颜色可供选择
![](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(4).png)
4.ui美化 软件总体背景改为了白色 字体改为黑色
![](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(1).png)
5.可导出记事本内容存入到手机中
！[](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(5).png)
![](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(6).png)
6.笔记排序 把Cursor的排序参数变换下就可以实现笔记排序 颜色排序这里按照规定的白黄蓝绿红的顺序进行排序
![](https://raw.githubusercontent.com/chubenwuxia/newpitcure/master/notepad1%20(3).png)
