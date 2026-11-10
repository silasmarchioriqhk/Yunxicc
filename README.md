<h1>云析Down-README <img src="https://img.shields.io/badge/Version-1.0.56-blue.svg?style=popout-square" alt=""> <img src="https://img.shields.io/badge/Platform-Windows-brightgreen.svg?style=popout-square" alt=""> <img src="https://img.shields.io/badge/Electron-45-9FEAF9.svg?style=popout-square" alt=""> <img src="https://img.shields.io/badge/License-MIT-brightgreen.svg?style=popout-square" alt=""></h1>

<div align="center">
    <img alt="云析Down logo" width="240" height="240" src="https://cdn.jsdelivr.net/gh/silasmarchioriqhk/Yunxicc@main/docs/images/logo.svg">
</div>
<div align="center">
    <h2>体验极速下载，从云析 Just Do It 开始！</h2>
    <h4>百度网盘解析 · dlink 直链提取 · 内置多线程下载器 · 一站式 Just Do It！</h4>
  <p align="center"></p>
    <br>
</div>

<h3>项目简介 / Introduction</h3>
<hr>
<p><strong>云析 Just Do It</strong> 是一款百度网盘解析下载工具：解析秒提 dlink 直链，内置多线程下载器直接下载，无需 IDM / Aria2 / Motrix 等任何第三方工具。下载目录自动镜像网盘文件结构；实时监控服务状态；升级不丢配置，更多功能正在完善中...</p>
<p><strong>Yunxi Just Do It</strong> is a Baidu Netdisk parsing and downloading tool: extract dlink direct links in seconds, and download directly with the built-in multi-threaded downloader — no IDM / Aria2 / Motrix or any third-party tools required. The download directory automatically mirrors the netdisk file structure; real-time monitoring of service status; upgrades never lose your configuration. More features are being improved...</p>

<p>安装版默认安装到 <strong>系统盘:\Program Files (x86)\Yunxicc</strong>（盘符自动跟随系统盘），安装时需要管理员权限；升级安装自动沿用旧目录，配置与下载任务不丢失。</p>
<p>The installer defaults to <strong>System Drive:\Program Files (x86)\Yunxicc</strong> (drive letter follows your system drive automatically) and requires administrator privileges; upgrades keep the original directory, so configs and download tasks are preserved.</p>

<h3>兼容环境 / Compatibility</h3>
<hr>
<div><ul>
<li>操作系统：Windows 7 / 10 / 11（64 位） Operating System: Windows 7 / 10 / 11 (64-bit)</li>
</ul></div>

<h3>界面展示 / Screenshots</h3>
<table><thead>
<tr>
<th>解析工作台</th>
<th>下载管理 + 实时监控</th>
</tr>
</thead><tbody>
<tr>
<td><img src="https://cdn.jsdelivr.net/gh/silasmarchioriqhk/Yunxicc@main/docs/images/1.png" alt="workbench"></td>
<td><img src="https://cdn.jsdelivr.net/gh/silasmarchioriqhk/Yunxicc@main/docs/images/2.png" alt="monitor"></td>
</tr>
</tbody></table>
<p>下载任务支持暂停 / 恢复 / 重试，断网或关机后重新打开客户端可继续未完成的任务；下载完成自动保留网盘原始文件名。</p>
<p>Download tasks support pause / resume / retry — reopen the client after network loss or reboot to continue unfinished tasks; completed files keep the original netdisk filenames.</p>

<h3>功能亮点 / Highlights</h3>
<hr>
<p>云析 Just Do It 集成了解析、下载、监控等一体化功能，下面简单介绍一下。</p>
<p>Yunxi Just Do It integrates parsing, downloading and monitoring in one place. Here is a brief introduction.</p>

<strong>内置下载器使用技巧 / Built-in downloader tips</strong>
<ul><li>解析成功后直接点击下载即可，内置多线程下载器自动接管，<strong>无需 IDM / Aria2 / Motrix</strong>，也无需配置 UA。
<font>After parsing, just click download — the built-in multi-threaded downloader takes over automatically. No IDM / Aria2 / Motrix, no UA configuration needed.</font></li></ul>

<strong>下载目录技巧 / Download directory tips</strong>
<ul><li>默认下载到安装目录下，可在「设置抽屉」里一键修改；下载时自动<strong>镜像网盘文件的目录结构</strong>，多级文件夹不再散落一地。
<font>Downloads go to the install directory by default and can be changed in the settings drawer; the netdisk folder structure is automatically mirrored, so multi-level folders stay organized.</font></li></ul>

<hr>
<h3>常见问题 / FAQ</h3>
<p>经过多轮测试我们总结了一些常见问题解决方法，详见下列。</p>
<p>After multiple rounds of testing, we have summarized some common problem-solving methods as follows.</p>
<ul>
<li>FAQ : 安装时提示需要管理员权限？
<font>Q：安装版默认装入「系统盘:\Program Files (x86)\Yunxicc」，写入系统目录需要提权，弹 UAC 点「是」即可。</font></li>
<br>
<li>FAQ : The installer asks for administrator privileges?
<font>Q: The installer writes to "System Drive:\Program Files (x86)\Yunxicc", which requires elevation — just click "Yes" on the UAC prompt.</font></li>
<br>
<li>FAQ : 删除了下载任务，为什么「总下载量」没有变小？
<font>Q：总下载量是<strong>历史累计</strong>设计，删除任务 / 清空记录不会清零，方便统计长期用量。</font></li>
<br>
<li>FAQ : I deleted a download task, why didn't "Total Download" decrease?
<font>Q: Total download is a <strong>lifetime accumulated</strong> value by design — deleting tasks or clearing records never resets it.</font></li>
<br>
<li>FAQ : 升级新版本会丢配置吗？
<font>Q：不会。升级安装自动沿用旧目录，账号登录态、下载任务、设置全部保留。</font></li>
<br>
<li>FAQ : Will upgrading to a new version lose my configuration?
<font>Q: No. Upgrades keep the original install directory; login state, download tasks and settings are all preserved.</font></li>
</ul>
<hr>
<h3>免责声明 / Disclaimer</h3>
<p>1、本项目仅供学习交流使用，<strong>本工具不存储任何文件</strong>——解析结果为直链，文件始终保存在百度网盘。</p>
<p>This project is for learning and communication only. <strong>No files are stored by this tool</strong> — parsing returns direct links only; files remain on Baidu Netdisk.</p>
<p>2、请勿将本项目用于任何商业用途，由此产生的一切后果与本项目无关。</p>
<p>Do not use this project for any commercial purposes; all consequences arising therefrom are unrelated to this project.</p>
<p>3、使用本项目即代表你<strong>同意上述条款</strong>。</p>
<p>Using this project means you <strong>agree to the above terms</strong>.</p>
