# Typora-free
note
安装Typora
[注意安装1.95版及之前的版本](https://typora.io/releases/all}，不要安装在C盘。

安装完成之后，按照以下路径寻找文件
<img width="953" height="663" alt="image" src="https://github.com/user-attachments/assets/75f5cef9-fed0-48fd-911a-921c49cc40ce" />

查找：e.hasActivated="true"==e.hasActivated,
替换成：e.hasActivated="true"=="true",
<img width="1898" height="1090" alt="image" src="https://github.com/user-attachments/assets/be53d876-06de-44f9-a77b-f1b24ef73481" />

保存后重启Typora提示已激活
<img width="1369" height="1207" alt="image" src="https://github.com/user-attachments/assets/2f56d34f-b2bd-4eaa-8c57-e7452e8043c1" />

关闭已激活弹窗 [可选]
编辑修改Typora安装目录下文件
<img width="840" height="786" alt="image" src="https://github.com/user-attachments/assets/084c8c6b-d74d-4b42-9ee3-58f83a3f3cee" />
查找：</body></html>
替换成：</body><script>window.onload=function(){setTimeout(()=>{window.close();},300);}</script></html>
<img width="1898" height="1090" alt="image" src="https://github.com/user-attachments/assets/e71b0377-2fe8-493a-a2ad-eb372e71e451" />
保存后重启Typora，激活弹窗300毫秒后自动关闭，不过可能会报错，可以尝试增加时间，如果还经常报错，可以跳过这一步，每次手动关闭


隐藏左下角“未激活”文字
编辑修改Typora安装目录下文件
<img width="902" height="428" alt="image" src="https://github.com/user-attachments/assets/6e176c7b-24b5-401b-96a2-b2e2acb9719a" />
查找："UNREGISTERED":"未激活",
替换："UNREGISTERED":" ",
<img width="1898" height="1090" alt="image" src="https://github.com/user-attachments/assets/7325cc6d-64cf-4138-81a5-e2d27e030d8b" />
