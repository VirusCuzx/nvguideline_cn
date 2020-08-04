<p class="has-line-data" data-line-start="0" data-line-end="1">一、安装设置</p>
<p class="has-line-data" data-line-start="2" data-line-end="4">1.系统设置：<br>
如果之前卸载过新维加斯，<strong>请确保删除所有了游戏文件、相关存档并清除注册表残余</strong>。如果使用Windows 10系统，请修改以下设置：</p>
<ul>
<li class="has-line-data" data-line-start="5" data-line-end="6">关闭系统自带的游戏模式</li>
<li class="has-line-data" data-line-start="6" data-line-end="7">单独添加英语作为第二语言，并在游戏时确保切换到英语键盘。</li>
<li class="has-line-data" data-line-start="7" data-line-end="9">游戏时关掉所有通知，以及其他可能在后台弹出的软件。</li>
</ul>
<p class="has-line-data" data-line-start="9" data-line-end="11"><strong>安装所有需要的Microsoft VC++ Redistributable Packages</strong>，如果没有请下载以下压缩包并安装里面的所有文件<br>
<a href="https://pan.baidu.com/s/1Z2qHznIQXqfGuY2Sg1l9tQ">https://pan.baidu.com/s/1Z2qHznIQXqfGuY2Sg1l9tQ</a> 提取码: 678q</p>
<p class="has-line-data" data-line-start="12" data-line-end="15">2.安装设置：<br>
<strong>如果还没有安装游戏，请不要安装在 C:/Program Files(x86)/Steam 文件夹</strong>（如果已经按照在上述文件夹则无法使用BSA Decompressor）<br>
常用目录：</p>
<ul>
<li class="has-line-data" data-line-start="16" data-line-end="17">根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em></li>
<li class="has-line-data" data-line-start="17" data-line-end="19">Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em></li>
</ul>
<p class="has-line-data" data-line-start="19" data-line-end="21"><strong>3.禁用叠加层</strong>：<br>
需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<ul>
<li class="has-line-data" data-line-start="22" data-line-end="23">Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</li>
<li class="has-line-data" data-line-start="23" data-line-end="25">GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</li>
</ul>
<p class="has-line-data" data-line-start="25" data-line-end="27">4.首次运行以初始化ini文件：<br>
<strong>在Steam或GOG中启动游戏，等待其完成初始化设置</strong>。完成后弹出Detecting Video Hardware的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li class="has-line-data" data-line-start="28" data-line-end="30">如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行</li>
</ul>
<p class="has-line-data" data-line-start="30" data-line-end="32">选择 Options，确认游戏检测到并正确使用你的GPU，并选择了合适画质（建议不要选择最低画质）。<br>
根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。单击 OK，然后单击 PLAY 进入游戏。进入主菜单后没有异常就可以退出游戏。</p>
<p class="has-line-data" data-line-start="33" data-line-end="34">二、汉化安装</p>
<p class="has-line-data" data-line-start="35" data-line-end="43">本指南使用民间汉化第六版，首先请确保可以正常进入游戏，然后下载汉化补丁<br>
<a href="https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA">https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv<br>
双击汉化补丁进行安装，一路点击下一步。<br>
<strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。<br>
在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简洁安装，<strong>只需要汉化必须文件</strong>。<br>
点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1<br>
点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置<br>
<img src="https://s1.ax1x.com/2020/07/07/UFhJVH.jpg" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li class="has-line-data" data-line-start="43" data-line-end="44">首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="44" data-line-end="45">然后勾选 2 所有的框，<strong>保持 3 中的三个数字为默认</strong></li>
<li class="has-line-data" data-line-start="45" data-line-end="47">在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>
</ul>
<p class="has-line-data" data-line-start="47" data-line-end="51">GOG版汉化后必需文件：<br>
<a href="https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ">https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7<br>
特殊安装说明：<br>
将压缩包内的文件解压到根目录（文件来源于网络，没有GOG版无法验证是否起作用）</p>
<blockquote>
<p class="has-line-data" data-line-start="51" data-line-end="53">汉化补丁使用了Steam版的exe文件并进行了修改，打上补丁的GOG版就相当于Steam版。<br>
天邈汉化使用原版exe文件，目前天邈插件尚不完善，<strong>不推荐使用天邈与民间汉化混装的模式</strong>。</p>
</blockquote>
<p class="has-line-data" data-line-start="54" data-line-end="55">此时汉化已经完成，进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容汉化是否有问题。</p>
<p class="has-line-data" data-line-start="56" data-line-end="57">三、BSA文件优化</p>
<p class="has-line-data" data-line-start="58" data-line-end="59"><strong>这一步要求游戏安装在 C:/Program Files(x86)/Steam 文件夹之外，如果不满足则跳过</strong></p>
<p class="has-line-data" data-line-start="60" data-line-end="68">BSA Decompressor<br>
<a href="https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw">https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw</a> 提取码: xmjd<br>
特殊安装说明：<br>
<strong>如果使用机械硬盘或正在/计划使用TTW，则不要安装</strong><br>
将下载的文件解压缩到除Windows默认文件夹外的安全位置<br>
右键单击FNV BSA Decompressor.exe，选择以管理员身份运行<br>
打开程序后，应该自动检测到游戏所在目录，如果没有请自行导航到 Fallout New Vegas 文件夹<br>
点击 Decompressor 开始运行，完成后点击 EXIT 退出程序</p>
<p class="has-line-data" data-line-start="69" data-line-end="76">四、调整FalloutCustom.ini<br>
导航到 文档/My Games/FalloutNV，新建一个文本文档，重命名为FalloutCustom.ini<br>
打开FalloutCustom.ini，将以下内容粘贴到文档中：<br>
[General]<br>
bUseThreadedAI=1<br>
INumHWThreads=4<br>
bPreemptivelyUnloadCells=1</p>
<p class="has-line-data" data-line-start="77" data-line-end="80">[BackgroundLoad]<br>
bBackgroundCellLoads=1<br>
bSelectivePurgeUnusedOnFastTravel=1</p>
<p class="has-line-data" data-line-start="81" data-line-end="84">[Display]<br>
bFull Screen=1<br>
iPresentInterval=1</p>
<p class="has-line-data" data-line-start="85" data-line-end="92">[Controls]<br>
fForegroundMouseAccelBase=0<br>
fForegroundMouseAccelTop=0<br>
fForegroundMouseBase=0<br>
fForegroundMouseMult=0<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</p>
<p class="has-line-data" data-line-start="93" data-line-end="95">[Grass]<br>
fGrassStartFadeDistance=7000</p>
<p class="has-line-data" data-line-start="96" data-line-end="99">[Audio]<br>
iAudioCacheSize=8192<br>
iMaxSizeForCachedSound=1024</p>
<p class="has-line-data" data-line-start="100" data-line-end="102">[Archive]<br>
SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa</p>
<ul>
<li class="has-line-data" data-line-start="103" data-line-end="104">
<p class="has-line-data" data-line-start="103" data-line-end="104">将INumHWThreads更改为CPU所具有的线程数，可以打开同目录下的RendererInfo.txt ，对应最后一行 HW Thread Count后面的数字</p>
</li>
<li class="has-line-data" data-line-start="104" data-line-end="108">
<p class="has-line-data" data-line-start="104" data-line-end="107">如果你不以16：9的宽高比运行游戏，可以删除<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</p>
</li>
<li class="has-line-data" data-line-start="108" data-line-end="109">
<p class="has-line-data" data-line-start="108" data-line-end="109">如果使用G/Free-sync，则iPresentInterval可以设置为0</p>
</li>
<li class="has-line-data" data-line-start="109" data-line-end="111">
<p class="has-line-data" data-line-start="109" data-line-end="110">如果没有使用BSA Decompressor，请删除[Archive]及下面的内容</p>
</li>
</ul>
<p class="has-line-data" data-line-start="111" data-line-end="112">完成后保存关闭。</p>
<p class="has-line-data" data-line-start="113" data-line-end="114">五、重要前置</p>
<p class="has-line-data" data-line-start="115" data-line-end="121">前置补丁包<br>
<a href="https://pan.baidu.com/s/1GvKqkBfxCLWwPzoNb9BDpg">https://pan.baidu.com/s/1GvKqkBfxCLWwPzoNb9BDpg</a> 提取码：tyg1<br>
特别安装说明：<br>
在安装前，请确保安装了所有需要的Microsoft VC++ Redistributable Packages(见第一步)<br>
将压缩包内的所有内容解压到根目录，并在出现提示时选择覆盖，解压后nvse_loader.exe应该与FalloutNV.exe在同一目录。<br>
对exe文件进行4gbPatch：</p>
<p class="has-line-data" data-line-start="122" data-line-end="125"><strong>针对修改版exe文件(民间汉化，目前本指南使用)</strong>：<br>
导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行<br>
在弹出的窗口中双击选择 FalloutNV.exe ，等待根目录下出现 FalloutNV.exe.Backup 后点击 OK 退出</p>
<p class="has-line-data" data-line-start="126" data-line-end="129"><strong>针对原版exe文件(天邈汉化，本指南没有使用)</strong>：<br>
导航到根目录，右键单击 FalloutNVpatch.exe ，选择 以管理员身份运行<br>
弹出的窗口中应该显示 FalloutNV.exe patched! ，按键盘上的任意键退出</p>
<ul>
<li class="has-line-data" data-line-start="130" data-line-end="132">个人制作的前置补丁包，包含必要前置及优化文件。具体内容详见 <strong><a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md" title="前置说明">前置说明</a></strong></li>
</ul>
<p class="has-line-data" data-line-start="132" data-line-end="136"><strong>验证NVSE和4GBpatch是否运行：</strong><br>
在根目录下双击nvse_loader.exe运行游戏。进入游戏主菜单后，按 ~ 键打开控制台<br>
将getnvseversion输入控制台并按Enter键，控制台应报告 NVSE version: 5<br>
将getislaa输入控制台并按Enter键，控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li class="has-line-data" data-line-start="137" data-line-end="139">如果没有，请检查前置包是否正确安装</li>
</ul>
<p class="has-line-data" data-line-start="139" data-line-end="140"><strong>验证完成后，不要在Steam/GOG内运行游戏，只通过NVSE(nvse_loader.exe)进行游戏</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="141" data-line-end="143">使用民间汉化后，运行游戏不再需要强制打开Steam，如果需要成就请提前打开平台<br>
通过Steam或GOG验证游戏文件完整性可以恢复原版exe文件，但会撤消4GBpatch补丁</p>
</blockquote>
<p class="has-line-data" data-line-start="144" data-line-end="145">七、最终测试</p>
<p class="has-line-data" data-line-start="146" data-line-end="147">至此基础游戏的设置及优化已全部完成，请按照以下步骤进行完整测试：</p>
<ul>
<li class="has-line-data" data-line-start="148" data-line-end="149">确保选择了合适的画质选项，之后通过NVSE进行游戏</li>
<li class="has-line-data" data-line-start="149" data-line-end="150">启动一个新存档，快速通过医生的教程</li>
<li class="has-line-data" data-line-start="150" data-line-end="151">离开医生的房间后，打开pipboy检查各个选项是否有问题</li>
<li class="has-line-data" data-line-start="151" data-line-end="153">在游戏中花费至少10分钟做任何事情以确保游戏顺利进行</li>
</ul>
<hr>
<p class="has-line-data" data-line-start="155" data-line-end="156">以上是基础汉化的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到现代化的新维加斯体验。</p>
