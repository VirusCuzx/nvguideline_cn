

<p class="has-line-data" data-line-start="0" data-line-end="1">一、一般信息</p>
<p class="has-line-data" data-line-start="2" data-line-end="4">关于游戏你需要了解的信息有：<br>
请先确保自己的电脑能够运行新维加斯，游戏运行不稳定也可能是硬件配置造成的。</p>
<p class="has-line-data" data-line-start="5" data-line-end="6">本指南只推荐Steam或GOG的正版终极版，也就是全DLC的版本。</p>
<p class="has-line-data" data-line-start="7" data-line-end="8">汉化补丁使用民间汉化第6版， <strong>注意它只支持终极版或者安装了所有dlc的版本</strong>。</p>
<blockquote>
<p class="has-line-data" data-line-start="9" data-line-end="10">汉化补丁使用Steam版的exe文件替换了原文件，因此打上补丁的GOG版就相当于Steam版</p>
</blockquote>
<p class="has-line-data" data-line-start="11" data-line-end="13">对于本指南你需要了解的信息有：<br>
入门指南只针对原版游戏进行优化，不会添加或修改游戏内容。</p>
<p class="has-line-data" data-line-start="14" data-line-end="15">该指南以纯操作指南的方式编写，只要<strong>按照顺序</strong>执行步骤即可以达到效果。</p>
<p class="has-line-data" data-line-start="16" data-line-end="17">本指南完成所需的时间并不长，强烈建议完整读一遍指南再开始安装。</p>
<p class="has-line-data" data-line-start="18" data-line-end="19"><strong>建议每进行完一个大步骤后运行游戏</strong>，这样出错误后更快找到问题所在。</p>
<blockquote>
<p class="has-line-data" data-line-start="20" data-line-end="21">一些基础常识如Windows文件系统、解压缩以及INI文件的编辑修改等还是建议有所了解。</p>
</blockquote>
<p class="has-line-data" data-line-start="22" data-line-end="23">二、系统设置</p>
<p class="has-line-data" data-line-start="24" data-line-end="25">如果使用Win10，建议更新到较新的版本。Win10设置优化的选项很多，这里主要说三点影响较大的：</p>
<ul>
<li class="has-line-data" data-line-start="26" data-line-end="27">关闭系统自带的游戏模式</li>
<li class="has-line-data" data-line-start="27" data-line-end="28">单独添加英语作为第二语言，并在游戏时按alt+shift切换到英语键盘。</li>
<li class="has-line-data" data-line-start="28" data-line-end="30">关掉所有通知，以及其他可能在后台弹出的软件。</li>
</ul>
<p class="has-line-data" data-line-start="30" data-line-end="31"><strong>如果你之前安装过新维加斯后卸载，为保证本指南的能正常安装，请确保删除所有游戏文件、相关存档及注册表残余</strong>。方法是卸载后再搜索Fallout NV相关的文件及文件夹并删除，运行注册表清理工具删除相关残余条目。</p>
<p class="has-line-data" data-line-start="32" data-line-end="33">三、游戏安装</p>
<p class="has-line-data" data-line-start="34" data-line-end="38">1.安装参数：<br>
<strong>游戏本体确保安装在Steam默认文件夹之外(C:/Program Files(x86)/Steam)</strong><br>
所有modding工具必须安装在默认Windows文件夹之外（如Program Files，Program Files（x86）和Documents）。<br>
Fallout New Vegas和Mod Organizer 2必须安装在同一个盘上，但不要将Mod Organizer 2和mod文件夹安装在游戏根目录下。</p>
<p class="has-line-data" data-line-start="39" data-line-end="43">2.常用术语：<br>
根文件夹(根目录)：<em>Steam/steamapps/common/Fallout New Vegas</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas</em><br>
Data文件夹：<em>Steam/steamapps/common/Fallout New Vegas/Data</em> 或 <em>GOG Galaxy/Games/Fallout New Vegas/Data</em><br>
MO2：Mod Organizer 2</p>
<p class="has-line-data" data-line-start="44" data-line-end="46"><strong>3.禁用叠加层：</strong><br>
需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。</p>
<ul>
<li class="has-line-data" data-line-start="46" data-line-end="47">Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</li>
<li class="has-line-data" data-line-start="47" data-line-end="49">GeForce Experience的禁用方法为：打开GeForce Experience，点击右上方的齿轮图标进入设置。在 常规 一栏关闭 游戏内覆盖</li>
</ul>
<p class="has-line-data" data-line-start="49" data-line-end="53">4.设置Fallout New Vegas Modding文件夹：<br>
modding文件夹将充当安装的所有工具的主目录，以及任何备份/屏幕截图等<br>
在与Fallout New Vegas相同盘上的默认Windows文件夹和游戏根目录之外创建一个新文件夹，将它命名为<em>Fallout NV Modding</em>，创建两个子文件夹名为<em>Backups</em>和<em>Tools</em><br>
备份整个游戏，将 Fallout New Vegas 文件夹复制到刚才创建的 Backups 中。</p>
<p class="has-line-data" data-line-start="54" data-line-end="57"><strong>5.运行游戏以初始化ini文件：</strong><br>
从根文件夹运行 FalloutNVLauncher.exe<br>
弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p>
<ul>
<li class="has-line-data" data-line-start="58" data-line-end="60">如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</li>
</ul>
<p class="has-line-data" data-line-start="60" data-line-end="62">选择 Options<br>
确认游戏检测到并正确使用你的GPU，并选择了合适画质。</p>
<ul>
<li class="has-line-data" data-line-start="62" data-line-end="64">如果没有正确识别GPU，请手动选择并调整画质选项</li>
</ul>
<p class="has-line-data" data-line-start="64" data-line-end="66">根据你的偏好设置分辨率，注意 Antiailiasing 项最多可以设置为8 Samples。<br>
单击 OK，然后单击 PLAY 进入游戏。进入主菜单后点击 Quit 然后 Exit Game 退出游戏。</p>
<ul>
<li class="has-line-data" data-line-start="66" data-line-end="68">如果无法正常进入游戏，请参照步骤五为exe文件添加排除数据执行保护，再进行尝试</li>
</ul>
<p class="has-line-data" data-line-start="68" data-line-end="69">四、一些工具</p>
<p class="has-line-data" data-line-start="70" data-line-end="75">1.Microsoft VC ++ 2013<br>
<a href="http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe">http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe</a><br>
特别安装说明：<br>
运行安装程序并按照给定的说明操作<br>
如果您收到已安装该程序的消息，请退出安装程序</p>
<ul>
<li class="has-line-data" data-line-start="75" data-line-end="77">FNV和4GB Patcher所需的库</li>
</ul>
<p class="has-line-data" data-line-start="77" data-line-end="85">2.Microsoft VC ++ 2015,2017,2019<br>
<a href="https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads">https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads</a><br>
特别安装说明：<br>
单击Visual Studio 2017标题下的x86：vc_redist.x86.exe和x64：vc_redist.x64.exe链接<br>
运行两个.exe文件并按照说明安装它们<br>
如果您收到已安装该程序的消息，请退出安装程序<br>
对于非Win10用户，则可能还需要遵循以下说明<br>
<a href="https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows">https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows</a></p>
<ul>
<li class="has-line-data" data-line-start="85" data-line-end="87">Mod Organizer 2和NVGE所需的库</li>
</ul>
<p class="has-line-data" data-line-start="87" data-line-end="96">3.Mod Organizer 2<br>
<a href="https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg">https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg</a> 提取码: hh7g<br>
特别安装说明：<br>
下载 Mod Organizer 2 (Archive) 主文件<br>
在之前Fallout NV Modding文件夹下的Tools文件夹新建一个文件夹命名为Mod Organizer 2<br>
解压缩所有文件到 Mod Organizer 2 文件夹，进入目录右键单击 ModOrganizer.exe 并选择 属性<br>
导航到 兼容性 选项卡，然后选中 以管理员身份运行此程序<br>
选择 应用 然后单击确定退出<br>
退出后暂时不要打开ModOrganizer.exe</p>
<ul>
<li class="has-line-data" data-line-start="96" data-line-end="98">迄今为止新维加斯最佳mod管理器，利用虚拟文件系统保持Data文件夹干净</li>
</ul>
<p class="has-line-data" data-line-start="98" data-line-end="99">五、汉化安装</p>
<p class="has-line-data" data-line-start="100" data-line-end="108">首先请确保可以正常进入游戏，下载汉化补丁<br>
<a href="https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA">https://pan.baidu.com/s/1CS-upRW02WvEyTZPipjkVA</a> 提取码: 7miv<br>
双击汉化补丁进行安装，一路点击下一步。<br>
<strong>在 选择目标位置 界面检查安装位置是否正确</strong>。下一步时会弹出对话框提示目录已经存在，点击 是 即可。<br>
在 选择组件 界面中反选所有选项，或在下拉菜单中选择 简介安装，<strong>只需要汉化必须文件</strong>。<br>
点击下一步进行安装，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1<br>
点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置<br>
<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true" alt="fnvtools_pic" title="fnvtools_pic"></p>
<ul>
<li class="has-line-data" data-line-start="109" data-line-end="110">首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开  RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="110" data-line-end="111">然后勾选 2 所有的框，<strong>保持 3 中的三个数字为默认</strong> (下面的优化会涉及此项)</li>
<li class="has-line-data" data-line-start="111" data-line-end="113">在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li>
</ul>
<p class="has-line-data" data-line-start="113" data-line-end="115">为exe文件添加排除数据执行保护：<br>
右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p>
<p class="has-line-data" data-line-start="116" data-line-end="121">GOG版汉化后必需文件：<br>
<a href="https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ">https://pan.baidu.com/s/1JlGDAt0TlkvA1dmtYrdIHQ</a> 提取码: s5x7<br>
特殊安装说明：<br>
将压缩包内的文件解压到根目录<br>
（文件来源于网络，没有GOG版无法验证是否起作用）</p>
<p class="has-line-data" data-line-start="122" data-line-end="123">进入游戏，主界面和菜单应该都已汉化。<strong>点击 选项-显示 ，滚轮滑到最下，将 一般字幕 设置为开启</strong>。后退到主菜单，开始新游戏测试游戏内容及汉化是否有问题。</p>
<p class="has-line-data" data-line-start="124" data-line-end="125">六、BSA文件与音频解码优化</p>
<p class="has-line-data" data-line-start="126" data-line-end="128">BSA Decompressor<br>
<a href="https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw">https://pan.baidu.com/s/1wVpaMcmghl2xpl3Xu9oqHw</a> 提取码: xmjd</p>
<p class="has-line-data" data-line-start="129" data-line-end="130"><em><em>这一步要求游戏本体安装在</em>C:/Program Files(x86)/Steam</em>之外，如果没有则跳过本步骤，直接进行Ogg Vorbis Libraries**</p>
<p class="has-line-data" data-line-start="131" data-line-end="138">特殊安装说明：<br>
如果使用机械硬盘或正在/计划使用TTW，则不要安装<br>
将下载的文件解压缩到Modding文件夹中<br>
右键单击FNV BSA Decompressor.exe，选择以管理员身份运行<br>
打开程序后，应该自动检测到游戏所在目录，如果没有请自行导航到Fallout New Vegas文件夹<br>
点击 Decompressor 开始运行，完成后点击 EXIT 退出程序<br>
退出后，导航至根文件夹删除 libogg.dll</p>
<ul>
<li class="has-line-data" data-line-start="138" data-line-end="140">优化BSA文件，提升加载速度并解决一些音频播放的问题</li>
</ul>
<p class="has-line-data" data-line-start="140" data-line-end="145">Ogg Vorbis Libraries<br>
<a href="https://pan.baidu.com/s/1k2s5nkiEYoh_ySpOe0hp2w">https://pan.baidu.com/s/1k2s5nkiEYoh_ySpOe0hp2w</a> 提取码: ympj<br>
特殊安装说明：<br>
将压缩包内的文件解压到根目录，并在出现提示时覆盖<br>
<strong>如果.dll文件被杀毒软件误报，请将其添加进白名单</strong></p>
<ul>
<li class="has-line-data" data-line-start="145" data-line-end="147">最新的Ogg Vorbis编译库，允许游戏播放某些.ogg文件</li>
</ul>
<p class="has-line-data" data-line-start="147" data-line-end="148">七、Mod Organizer 2配置及INI优化</p>
<p class="has-line-data" data-line-start="149" data-line-end="163">1.配置Mod Organizer 2：<br>
运行ModOrganizer.exe<br>
从名为 Choose Instance 的弹出窗口中，选择 Portable<br>
从弹出窗口 Please select the game to manage，选择 New Vegas<br>
如果未显示New Vegas选项，请选择 Browse…，然后导航到根文件夹并选择FalloutNV.exe<br>
如果有一个名为 INI file is read-only 的窗口，请选择 Yes<br>
从弹出窗口 Show Tutorial?，选择 No<br>
从弹出窗口 Register?，选择 Yes<br>
进入主界面，点击顶部的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true" alt="setting_pic" title="setting_pic"><br>
在 General 选项卡下第一栏 Language 项选择 Chinese (simplified)<br>
点击 OK 软件切换成中文<br>
如果未选中右栏中的所有插件，请右键单击右栏空白处并选择 全部启用<br>
按照下图中的顺序改变左栏和右栏中的加载顺序<br>
<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/order_pic.jpg?raw=true" alt="order_pic" title="order_pic"></p>
<ul>
<li class="has-line-data" data-line-start="164" data-line-end="166">如果您的游戏是GOG版本，则加载顺序中可能存在FalloutNV_lang.esp ，请导航到/Data文件夹并将其删除</li>
</ul>
<p class="has-line-data" data-line-start="166" data-line-end="169">单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true" alt="setting_pic" title="setting_pic">，导航到&quot; 路径&quot;选项卡<br>
如果您使用SSD或空间很小的HDD，请将 下载 路径设置为具有足够空间的某个位置<br>
MO2可以与Nexus账户连接，没有的可以跳过</p>
<ul>
<li class="has-line-data" data-line-start="169" data-line-end="170">在 N网 选项卡中，单击 Connect to Nexus ，MO2应在浏览器中打开Nexus页面</li>
<li class="has-line-data" data-line-start="170" data-line-end="171">选择 Authorise</li>
<li class="has-line-data" data-line-start="171" data-line-end="173">等待页面提示 You have successfully logged into Mod Organizer 2! 后退出浏览器</li>
</ul>
<p class="has-line-data" data-line-start="173" data-line-end="174">点击 OK 退出MO2中的设置菜单，如果MO2提示你重启，你应该选择 Yes</p>
<p class="has-line-data" data-line-start="175" data-line-end="184">2.在Mod Organizer 2中创建新配置文件：<br>
Mod Organizer 2的配置文件功能允许在不同的mod配置之间轻松切换，可以通过左栏上方的下拉菜单选择配置文件。<br>
单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2profile_pic.jpg?raw=true" alt="profile_pic" title="profile_pic"><br>
单击Default配置文件，然后选择重命名<br>
输入Vanilla作为新名称<br>
选中 Vanilla 配置文件，选择复制<br>
输入Core作为新名称，然后单击 OK<br>
选择 Core 配置文件并选中下方的 使用特定的ini (第二项，应该已经选中) 和 自动档案无效化<br>
关闭配置文件窗口，如果报错提示缺少ini文件，点击 OK 即可</p>
<p class="has-line-data" data-line-start="185" data-line-end="194">3.调整FalloutCustom.ini：<br>
确保目前选择的配置文件为 Core<br>
单击MO2顶部栏上的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true" alt="inieditor_pic" title="inieditor_pic"> ，然后选择 INI编辑器<br>
导航到 falloutcustom.ini 选项卡，该选项卡应为空白<br>
将以下内容粘贴到框中：<br>
[General]<br>
bUseThreadedAI=1<br>
INumHWThreads=4<br>
bPreemptivelyUnloadCells=1</p>
<p class="has-line-data" data-line-start="195" data-line-end="198">[BackgroundLoad]<br>
bBackgroundCellLoads=1<br>
bSelectivePurgeUnusedOnFastTravel=1</p>
<p class="has-line-data" data-line-start="199" data-line-end="213">[Display]<br>
fLightLODDefaultStartFade=10240.0<br>
fLightLODRange=10240.0<br>
fLightLODMinStartFade=10240.0<br>
fLightLODMaxStartFade=10240.0<br>
fShadowLODDefaultStartFade=200.0<br>
fShadowLODRange=200.0<br>
fShadowLODMinStartFade=100.0<br>
fShadowLODMaxStartFade=1000.0<br>
fSpecularLODDefaultStartFade=10240.0<br>
fSpecularLODRange=10240.0<br>
fSpecularLODMinStartFade=10240.0<br>
fSpecularLODMaxStartFade=10240.0<br>
iPresentInterval=0</p>
<p class="has-line-data" data-line-start="214" data-line-end="221">[Controls]<br>
fForegroundMouseAccelBase=0<br>
fForegroundMouseAccelTop=0<br>
fForegroundMouseBase=0<br>
fForegroundMouseMult=0<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</p>
<p class="has-line-data" data-line-start="222" data-line-end="224">[Grass]<br>
fGrassStartFadeDistance=17000</p>
<p class="has-line-data" data-line-start="225" data-line-end="228">[Audio]<br>
iAudioCacheSize=8192<br>
iMaxSizeForCachedSound=2048</p>
<ul>
<li class="has-line-data" data-line-start="229" data-line-end="230">将INumHWThreads更改为CPU所具有的线程数，可以导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li>
<li class="has-line-data" data-line-start="230" data-line-end="234">如果你不以16：9的宽高比运行游戏，可以删除<br>
fXenonVertLookSpeed=1200.0000<br>
fXenonHorizLookSpeed=1500.0000</li>
</ul>
<p class="has-line-data" data-line-start="234" data-line-end="235">完成后点击 保存 ，然后关闭INI编辑器。</p>
<p class="has-line-data" data-line-start="236" data-line-end="237">八、BethINI</p>
<p class="has-line-data" data-line-start="238" data-line-end="239"><a href="https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw">https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw</a> 提取码: jw7j</p>
<p class="has-line-data" data-line-start="240" data-line-end="242">注意事项：<br>
BethINI容易被防病毒软件标记为误报，所以最好请其添加到将杀毒软件的白名单中。<strong>请注意，不要通过Mod Organizer 2运行，也不要在Mod Organizer 2打开时运行BethINI</strong>。</p>
<p class="has-line-data" data-line-start="243" data-line-end="244">安装使用说明：</p>
<ol>
<li class="has-line-data" data-line-start="244" data-line-end="245">使用前请确保已运行过FalloutNVLauncher.exe并生成了相应的INI文件</li>
<li class="has-line-data" data-line-start="245" data-line-end="246"><strong>请确保Mod Organizer 2关闭</strong>，解压缩文件到 <em>/Fallout NV Modding/Tools</em> 文件夹，进入并运行 BethINI.exe 。在弹出的窗口中下拉选择 Fallout New Vegas ，等待进入程序。</li>
<li class="has-line-data" data-line-start="246" data-line-end="247">进入程序后导航到 Setup 选项卡， <strong>取消选择</strong>下方的全部选项方框。之后在 Mod Organizer 一栏下拉菜单中选择 Browse ,在弹出的框中导航到 Mod Organizer 2 文件夹并双击选择 ModOrganizer.exe</li>
<li class="has-line-data" data-line-start="247" data-line-end="248">在 INI Path 一栏下拉菜单中选择您现在使用的Mod Organizer 2配置文件，如 ModOrganizer&gt;Core 。在弹出对话框中选择 确定 。此时会弹出对话框提示BethINI要重新启动，点击 确定 。重启后会弹出名为 Modify Custom INIs? 对话框， <strong>此时选择 否</strong> 。重新进入BethINI后导航到 Setup 选项卡，请确保全部5个选择框都没有选择。</li>
<li class="has-line-data" data-line-start="248" data-line-end="249">导航到 Basic 选项卡，在 Presets 栏中选择 Vanilla Presets ，再选择 Recommended Tweaks ，程序会自动优化相应的INI文件，之后请根据配置在 Low 到 Ultra 中选择合适的画质选项。</li>
<li class="has-line-data" data-line-start="249" data-line-end="250">选择完画质后在 Display 一栏中选择合适的分辨率，如果没有需要的分辨率则可以手动输入。可以自行选择 Antialiasing 和 Anisotropic Filtering 倍数。最后选择最下方的 Enable File Selection (如果已经选择则不用管)，确定一切选择正确后点击 Save and Exit 退出。</li>
<li class="has-line-data" data-line-start="250" data-line-end="251">等待程序关闭后导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，查看下方 Shader Package 后的数字。如果不是19，请导航到游戏根目录下 <em>data/Shaders</em> 文件夹找到对应Shader Package后数字的文件，如 shaderpackage013.sdp ，将其命名为shaderpackage013.sdp.backup。之后把 shaderpackage019.sdp 复制一份到其他位置，将其重命名为shaderpackage013.sdp，再剪切回原文件夹。</li>
<li class="has-line-data" data-line-start="251" data-line-end="253">进入游戏，在主菜单中选择 选项-显示 ，检查所有<strong>淡出</strong>选项。如果有超出调节框的请将其减小一档，设置完成后退回主菜单，进入游戏检测运行是否正常。</li>
</ol>
<p class="has-line-data" data-line-start="253" data-line-end="255"><strong>在使用了BethINI之后，请不要运行FalloutNVLauncher.exe或通过Steam启动新维加斯，FNVTools2.1修改字体也将不起作用</strong>。<br>
如果在以后的游戏流程中需要修改画质、改变字体及其他选项，请阅读指南最后有关BethINI的说明。</p>
<p class="has-line-data" data-line-start="256" data-line-end="257">九、重要前置</p>
<p class="has-line-data" data-line-start="258" data-line-end="263">NVSE<br>
<a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a><br>
特别安装说明：<br>
单击 Download (stable version 5.1b4) 旁边的链接进行下载<br>
将压缩包内 nvse_5_1_beta4 文件夹中的所有内容解压到根目录</p>
<ul>
<li class="has-line-data" data-line-start="263" data-line-end="265">扩展引擎的脚本功能，对于大多数mod来说都是必不可少的</li>
</ul>
<p class="has-line-data" data-line-start="265" data-line-end="271">前置补丁包<br>
<a href="https://pan.baidu.com/s/1eiF8xBpgxPUn6neF-Q5ltw">https://pan.baidu.com/s/1eiF8xBpgxPUn6neF-Q5ltw</a> 提取码: m5zf<br>
特别安装说明：<br>
打开Mod Organizer2，单击顶栏的按钮<img src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2install_pic.PNG?raw=true" alt="install_pic" title="install_pic">，导航到下载好的压缩包，双击选择它。<br>
在弹出的窗口中确定名称为 Utilities ，点击 确定 安装补丁包。<br>
安装完成后该补丁会在左栏显示，选中 Utilities 前的方框以激活Mod。</p>
<ul>
<li class="has-line-data" data-line-start="271" data-line-end="273">个人制作的前置补丁包，包含必要前置补丁及修改好的优化文件。具体内容详见https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md</li>
</ul>
<p class="has-line-data" data-line-start="273" data-line-end="281">4GBpatch<br>
<a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h<br>
特殊安装说明：<br>
将压缩包内的 4gb_patch.exe 解压到根目录<br>
请确保 <strong>没有</strong>运行Mod Organizer 2，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行<br>
在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！<br>
此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，稍等一会<br>
在根目录出现 FalloutNV.exe.Backup 之后点击 OK 退出。</p>
<ul>
<li class="has-line-data" data-line-start="281" data-line-end="283">使游戏能够识别大地址，这意味着它可以使用4GB RAM而不是2GB</li>
</ul>
<p class="has-line-data" data-line-start="283" data-line-end="288"><strong>验证NVSE和4GBpatch是否运行：</strong><br>
打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行<br>
进入游戏主菜单后，按 ~ 键打开控制台<br>
将getnvseversion输入控制台并按Enter键<br>
控制台应报告 NVSE version: 5</p>
<ul>
<li class="has-line-data" data-line-start="288" data-line-end="290">如果没有，请检查NVSE是否已正确安装并重试</li>
</ul>
<p class="has-line-data" data-line-start="290" data-line-end="292">将getislaa输入控制台并按Enter键<br>
控制台应该报告 GetisLAA &gt;&gt; 2.0000</p>
<ul>
<li class="has-line-data" data-line-start="292" data-line-end="293">如果控制台报告 GetisLAA &gt;&gt; 0.0000，则说明补丁未正确安装</li>
<li class="has-line-data" data-line-start="293" data-line-end="294">如果控制台报告 GetisLAA &gt;&gt; 1.0000，则修补程序已正确安装但无法正常运行，尝试以管理员身份运行</li>
<li class="has-line-data" data-line-start="294" data-line-end="296">如果控制台报告错误消息，则表示您未正确安装JIP LN NVSE</li>
</ul>
<p class="has-line-data" data-line-start="296" data-line-end="297"><strong>验证完成，之后都在Mod Organizer 2中通过NVSE进行游戏</strong></p>
<blockquote>
<p class="has-line-data" data-line-start="297" data-line-end="298">通过Steam或GOG验证您的游戏文件将撤消4GBpatch补丁</p>
</blockquote>
<p class="has-line-data" data-line-start="299" data-line-end="300">十、最终测试</p>
<p class="has-line-data" data-line-start="301" data-line-end="302">至此基础游戏的设置及优化已全部完成，请按照以下步骤进行完整测试：</p>
<p class="has-line-data" data-line-start="303" data-line-end="307">通过MO2运行NVSE打开游戏<br>
启动一个新存档，快速通过Doc Mitchell所在的教程<br>
离开医生的房间后，打开pipboy检查各个选项是否有问题<br>
在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</p>
<ul>
<li class="has-line-data" data-line-start="307" data-line-end="308">如果按指南完整做到了每一个步骤，并选择了合适的画质与分辨率，此时游戏应没有卡顿并可以长时间运行不跳出。</li>
<li class="has-line-data" data-line-start="308" data-line-end="309">如果有任何问题，尝试先判断是否完全按指南进行设置。如果确定步骤没有问题，请先调低画质及分辨率再进行测试(但尽量不要以最低画质运行)。</li>
<li class="has-line-data" data-line-start="309" data-line-end="311">如果问题依旧存在，请尝试百度解决方法。也可以回复进行询问，我尽可能回答。</li>
</ul>
<p class="has-line-data" data-line-start="311" data-line-end="312">以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p>
