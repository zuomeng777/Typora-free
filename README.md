# Typora-free
## 1. 安装 Typora

请安装 Typora 1.9.5 或更早的版本，并选择 C 盘以外的安装位置。 [Typora 历史版本](https://typora.io/releases/all)

## 2. 修改安装目录中的文件

安装完成后，按下图所示路径找到对应文件。

<img width="572" alt="步骤截图 1" src="https://github.com/user-attachments/assets/75f5cef9-fed0-48fd-911a-921c49cc40ce" />

- **查找** `e.hasActivated="true"==e.hasActivated,`
- **替换为** `e.hasActivated="true"=="true",`

<img width="640" alt="步骤截图 2" src="https://github.com/user-attachments/assets/be53d876-06de-44f9-a77b-f1b24ef73481" />

保存文件并重启 Typora，查看激活提示。

<img width="640" alt="步骤截图 3" src="https://github.com/user-attachments/assets/2f56d34f-b2bd-4eaa-8c57-e7452e8043c1" />

## 3. 关闭激活弹窗（可选）

在 Typora 安装目录中打开下图所示的文件。

<img width="504" alt="步骤截图 4" src="https://github.com/user-attachments/assets/084c8c6b-d74d-4b42-9ee3-58f83a3f3cee" />

- **查找** `</body></html>`
- **替换为** `</body><script>window.onload=function(){setTimeout(()=>{window.close();},300);}</script></html>`

<img width="640" alt="步骤截图 5" src="https://github.com/user-attachments/assets/e71b0377-2fe8-493a-a2ad-eb372e71e451" />

保存后重启 Typora。弹窗会在 300 毫秒后自动关闭。如果报错，可以延长等待时间。若仍频繁报错，可以跳过此步骤并手动关闭弹窗。

## 4. 隐藏左下角的「未激活」文字

在 Typora 安装目录中打开下图所示的文件。

<img width="541" alt="步骤截图 6" src="https://github.com/user-attachments/assets/6e176c7b-24b5-401b-96a2-b2e2acb9719a" />

- **查找** `"UNREGISTERED":"未激活",`
- **替换为** `"UNREGISTERED":" ",`

<img width="640" alt="步骤截图 7" src="https://github.com/user-attachments/assets/7325cc6d-64cf-4138-81a5-e2d27e030d8b" />
