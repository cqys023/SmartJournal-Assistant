# SmartJournal-Assistant
智阅期刊助手
一个简洁高效的教育期刊/杂志 PDF 下载工具，支持多种教育类学术期刊资源，适用于 Windows 平台。用户可快速获取期刊目录、选择年份与期刊，并一键批量下载高清 PDF 文件。

🎯 功能亮点
✅ 支持多个教育类学术期刊资源

✅ 提供年份选择与期刊列表下拉选择

✅ 自动下载整期杂志为 PDF（按页面拼接）

✅ 支持下载进度条与状态提示

✅ 资讯模块：实时展示平台通知或更新

✅ 内置“期刊目录”快捷入口

✅ 自带资源名称选择与编号映射

✅ 使用多服务器智能切换，确保下载成功率

✅ 自动清理临时图片文件

✅ 支持简单资源编号手动输入

✅ 适合高校、教育研究人员、杂志订阅者使用

🖼️ 软件界面预览
软件采用 Tkinter 图形界面，界面简洁清晰。
<img width="1038" height="980" alt="image" src="https://github.com/user-attachments/assets/dd39860d-3bef-41d1-a3c0-26e917544252" />
<br>使用方法：
<img width="1026" height="970" alt="image" src="https://github.com/user-attachments/assets/894400cd-09bb-4f50-873e-601951bcdf67" />
<img width="1038" height="972" alt="image" src="https://github.com/user-attachments/assets/9928777a-e5ba-438b-9f00-92b273e05a69" />
<img width="1040" height="976" alt="image" src="https://github.com/user-attachments/assets/134fe711-71d9-42c6-8da4-56add4b92266" />
<img width="1032" height="972" alt="image" src="https://github.com/user-attachments/assets/4fb073f3-b102-42ae-9b3d-a25f05731585" />
<img width="1714" height="860" alt="image" src="https://github.com/user-attachments/assets/d82b588e-5fe4-45cc-b95b-5619417e7ead" />
下载完成后效果：
<br>
<img width="1086" height="1560" alt="image" src="https://github.com/user-attachments/assets/68f2b2a0-06c7-44ce-974a-df2f81c7c6cf" />
<img width="1082" height="1548" alt="image" src="https://github.com/user-attachments/assets/106cb70c-b495-4bf2-af07-1b46043e0ea0" />
部分期刊已停止更新，具体更新到哪年请从软件访问：期刊目录，
<img width="1028" height="976" alt="image" src="https://github.com/user-attachments/assets/d212ebde-100e-47ee-9da1-8871f43f45f8" />
<img width="1952" height="1648" alt="image" src="https://github.com/user-attachments/assets/f3ab0193-ab5a-4330-afd2-b808bc3293f4" />

🌐 资源来源说明
所有期刊图片资源来自网络搜索。

软件仅供学习研究交流使用，严禁用于商业目的。

📌 注意事项
某些服务器响应可能较慢，程序将自动切换备用服务器。

若下载失败，请检查网络环境或目标资源是否可用。

程序运行期间会下载临时图片，下载完成后自动清理。

💬 联系与反馈
欢迎提交 Issue 或 Fork 本项目进行修改。

📰 SmartJournal Assistant
SmartJournal Assistant is a lightweight, GUI-based educational journal and magazine downloader designed for researchers, students, and educators. It allows users to search, select, and download high-quality PDFs of journal issues from multiple education-related sources.

🚀 Features
✅ Support for a variety of academic and educational journals

✅ Easily select journal year and issue

✅ One-click download of entire journal issues as PDFs

✅ Download progress bar and status updates

✅ Embedded "News Info" section (auto-fetched from the web)

✅ Built-in quick access to the journal catalog

✅ Smart server fallback to ensure successful downloads

✅ Temporary image files are cleaned automatically

✅ Manual input supported for custom resource IDs

✅ Simple, user-friendly interface using Python's Tkinter

🖼️ Interface Overview
plaintext
复制
编辑
+--------------------------------------------+
| [Journal Resource Dropdown]                |
| Resource ID: [Auto-filled or Manual Input] |
| Year: [e.g., 2025]                         |
| [Open Catalog] [Fetch Journal List]        |
| [Issue Selection Dropdown]                 |
| [Download Selected Issue]                 |
| [Progress Bar + Status Label]              |
| [News Section (Auto-loaded)]              |
+--------------------------------------------+
🛠️ Installation & Usage
Requirements
Python 3.7 or above

Install required packages:

bash
复制
编辑
pip install requests Pillow fpdf
Run the App
bash
复制
编辑
python main.py
🔐 (Optional) Device Authentication
If your version includes device/MAC address authentication, please ensure your device is authorized before use. Contact the maintainer for authorization if needed.

⚠️ Notes
If some servers are slow or inaccessible, the tool will automatically try alternate image servers.

Please ensure you have a stable internet connection during downloading.

The app removes all temporary image files after PDF generation.

💡 Future Improvements
Auto year detection

Batch download of multiple issues

Offline issue archiving

📬 Feedback & Contribution
Feel free to open an Issue or Pull Request if you have suggestions or want to contribute.
