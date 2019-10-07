<body><h1 id="h1-2019-"><a name="2019年新维加斯入门指南" class="reference-link"></a><span class="header-link octicon octicon-link"></span>2019年新维加斯入门指南</h1><p><a href="http://github.com/feelbetterhua/nvguideline_cn">github.com/feelbetterhua/nvguideline_cn</a></p> <hr> <p><img title="intro" alt="intro" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/intro_pic.jpg?raw=true"><br> </p><p><strong>2019年了，新维加斯不应该是这个游戏体验</strong></p> <p>本指南旨在建立一种一站式的入门指导，帮助你了解游玩新维加斯需要的准备工作。并整合最新的优化配置选项，使你以最丝滑的方式体验废土的旅程。<br> </p><p>本指南不仅适新手，也面向准备回归的老兵。因为一些Mod和优化已与之前的方式不相兼容。<br> </p><p>本指南内容主要基于外网的一个MOD指南Viva New Vegas，但并非单纯将其汉化。本指南会根据中文补丁的安装修改一些流程。原指南地址： <em> <a href="http://vivanewvegas.github.io">vivanewvegas.github.io</a></em></p> <p>首先说一下结论，我使用一台笔记本电脑，配置为</p> <ul> <li>CPU：I7-5500U</li><li>内存：8GB 1666Mhz DDR3</li><li>显卡：GTX950m 2G DDR3</li><li>硬盘：128GB SATA3.0 SSD</li><li>系统：Win10 LTSC 2019</li></ul> <p>目前的设置优化可以使原版游戏在1080P，高画质下以满帧稳定运行。即使加了大量MOD后依旧可以在稍低分辨率下运行5~6个小时不跳出。<br> </p><p><strong>网上流传了很久新维加斯不适合在Win10上运行。以目前的情况看已经没有那么不堪，经过优化，Win10也可以完美运行。</strong></p> <p>一、一般信息<br> </p><p>在开始前，关于游戏你需要了解的信息有：<br> </p><p>请先确保自己的配置足够运行新维加斯。游戏中的许多问题有可能是配置不足导致的，当然通过本指南，你可以最大化发挥硬件的资源。</p> <p>对于版本的问题，本指南只推荐正版的终极版，也就是全DLC的版本，Steam或GOG的都可以。本指南编写时测试的版本为纯净的正版，其他版本不保证也有效果。</p> <p>本指南专门为汉化编写了相关内容，汉化补丁使用民间汉化第5版，这是目前最完善版本。 <strong>注意它只支持终极版即有全dlc的版本。</strong></p> <p>对于本指南你需要了解的信息有：<br> </p><p>本入门指南没有添加或修改游戏内容。如果你是你想通过MOD改变游戏玩法或内容，可以直接阅读原MOD指南。<br> </p><p>指南的目的是让所有人都可以快速上手，所以用纯操作指导的方式编写，只需<strong>按照顺序</strong>执行步骤就可以达到效果。<br> </p><p>本指南完成所需的时间并不长。强烈建议完整读过一遍指南，或至少读完整个步骤后再开始安装和设置。<br> </p><p>虽然本指南不需要太多相关经验即可上手，但一些基础常识如Windows文件系统、解压缩以及INI文件的编辑修改等还是建议有所了解。<br> </p><p>如果你是第一次使用本指南， <strong>建议你每执行一个大步骤就进行简单的游戏测试</strong>，这样你在出现错误时可以更快找到问题所在。</p> <p>二、系统设置<br> </p><p>如果你使用的是Win10，建议你更新到较新的系统。Win10系统可以设置优化的选项很多，这里主要说三点对新维加斯影响较大的：</p> <ul> <li>关闭系统自带的游戏模式，对于新维加斯来说该模式会造成不稳定</li><li>调整输入法，Win10自带的输入法会影响游戏。请单独添加英语作为第二键盘，并在游戏前按alt+shift切换到英语键盘。</li><li>关掉通知，以及其他可能在后台弹出对话框/提示的软件。新维加斯在切回桌面时很大概率会卡死，也建议在游玩过程中尽量不要切换窗口。</li></ul> <p>对于笔记本电脑，请确保电源选项选择正确，如高性能或卓越性能。而对于所用用户，请更新到较新的显卡驱动，并保证有足够的硬盘空间。<br> </p><p><strong>如果你之前安装过新维加斯后卸载，为保证本指南的能正常安装，请确保删除所有游戏文件、相关存档及注册表残余。</strong><br>具体方法是：卸载后搜索Fallout NV相关的文件及文件夹并删除，运行注册表清理工具删除相关残余条目。 </p><blockquote> <p>注册表清理工具推荐 Wise Registry Cleaner 或 CCleaner。</p> </blockquote> <p>三、游戏安装<br> </p><p>1.安装参数：<br> </p><p><strong>游戏本体必须安装在Steam默认安装文件夹之外<em>(C:/Program Files(x86)/Steam)</em>。</strong>如果安装在了Program Files(x86)文件夹，则无法使用BSA Comperessor优化。<br>所有modding工具必须安装在默认Windows文件夹之外（例如Program Files，Program Files（x86）和Documents）。<br>游戏本体和Mod Organizer 2必须安装在同一个盘上，但不要将Mod Organizer 2和mod文件夹安装在Fallout New Vegas根目录下。 </p><p>2.常用术语：<br> </p><p>根文件夹(根目录)： <em>Steam / steamapps / common / Fallout New Vegas</em> 或 <em>GOG Galaxy / Games / Fallout New Vegas</em><br> </p><p>Data文件夹： <em>Steam / steamapps / common / Fallout New Vegas / Data</em> 或 <em>GOG Galaxy / Games / Fallout New Vegas / Data</em><br> </p><p>MO2：Mod Organizer 2（将很快安装）</p> <p><strong>3.禁用叠加层：</strong><br> </p><p>需要为Fallout New Vegas禁用任何叠加以防止内存泄漏。一些具有覆盖的常见应用程序是Steam，GOG，NVIDIA GeForce Experience，Discord和MSI Afterburner。<br> </p><p>如Steam的禁用方法为：在库中右键点击Fallout：New Vegas，选择 属性，在 常规 选项卡下找到 在游戏中启动Steam界面 并反勾选它。</p> <blockquote> <p>这一步后将无法使用Steam自带的截图功能，完成成就时也不会有右下角弹窗，但是还是不建议启动叠加层。新维加斯游戏内有成就提示，后面也会介绍其他截图方式。</p> </blockquote> <p>4.设置Fallout New Vegas Modding文件夹：<br> </p><p>modding文件夹将充当所有工具的主目录，以及任何备份/屏幕截图等。从现在开始，此文件夹将被称为Modding文件夹。<br> </p><p>在与Fallout New Vegas相同的盘上的默认Windows文件夹之外创建一个新文件夹。将它命名<em>Fallout NV Modding</em>，并创建两个子文件夹名为<em>Backups</em>和<em>Tools</em><br> </p><p>备份整个游戏，将 Fallout New Vegas 文件夹复制到刚才创建的 Backups 中</p> <p>5.生成新鲜的.INI文件：<br> </p><p>从根文件夹运行 FalloutNVLauncher.exe<br> </p><p>弹出 Detecting Video Hardware 的窗口，单击确定。之后弹出窗口提示程序根据你的硬件已设置画质，单击确定。</p> <ul> <li>如果没有任何弹出窗口，请导航到 <em>文档/My Games/FalloutNV</em> 并删除以.INI结尾的所有文件，然后重新运行FalloutNVLauncher.exe</li></ul> <p>选择 Options<br> </p><p>确认游戏检测到并正确使用你的GPU，并选择了合适画质。如果没有正确识别GPU，请手动选择并调整画质选项。如果不确定，可以选Medium作为初始选项。<br> </p><p>根据你的偏好设置分辨率(启动器通常将其设置为低于最大分辨率的一个)。注意 Antiailiasing 项可以设置为8 Samples(启动器最多将其设置为4 Samples)。<br> </p><p>单击 OK，然后单击 PLAY 进入游戏。进入主菜单后点击 Quit 然后 Exit Game 退出游戏。</p> <ul> <li>如果无法正常进入游戏，请参照步骤五为exe文件添加排除数据执行保护，再进行尝试</li></ul> <p>四、一些工具<br> </p><p>1.Microsoft VC ++ 2013<br> </p><p><a href="http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe">http://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe</a><br> </p><p>特别安装说明：<br> </p><p>运行安装程序并按照给定的说明操作，如果您收到已安装该程序的消息，请退出安装。</p> <ul> <li>FNV和4GB Patcher所需的库</li></ul> <p>2.Microsoft VC ++ 2015,2017,2019<br> </p><p><a href="https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads">https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads</a><br> </p><p>特别安装说明：<br> </p><p>单击Visual Studio 2017标题下的x86：vc_redist.x86.exe和x64：vc_redist.x64.exe链接<br> </p><p>运行两个.exe文件并按照说明安装它们，如果您收到已安装该程序的消息，请退出安装程序。<br> </p><p>如果您不在Windows 10上，则可能还需要遵循以下说明<br> </p><p><a href="https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows">https://support.microsoft.com/en-us/help/2999226/update-for-universal-c-runtime-in-windows</a></p> <ul> <li>Mod Organizer 2和NVGE所需的库</li></ul> <p>3.Mod Organizer 2<br> </p><p><a href="https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg">https://pan.baidu.com/s/1V8QuKdi6dusXVTamwxnuPg</a> 提取码: hh7g<br> </p><p>特别安装说明：<br> </p><p>下载 Mod Organizer 2 (Archive) 主文件<br> </p><p>在之前Fallout NV Modding文件夹下的Tools文件夹新建一个文件夹命名为Mod Organizer 2<br> </p><p>解压缩所有文件到 Mod Organizer 2 文件夹，进入目录右键单击 ModOrganizer.exe 并选择 属性<br> </p><p>导航到 兼容性 选项卡，然后选中 以管理员身份运行此程序，选择 应用 然后单击确定退出<br> </p><p>退出后暂时不要打开ModOrganizer.exe，后面会在配置时打开。</p> <ul> <li>迄今为止新维加斯最佳的mod管理器，利用虚拟文件系统保持Data文件夹干净</li></ul> <p>4.MO2插件<br> </p><p><a href="https://pan.baidu.com/s/1yTJO6wxmiXbwtyH9DuMhPA">https://pan.baidu.com/s/1yTJO6wxmiXbwtyH9DuMhPA</a> 提取码: 28pm<br> </p><p>特别安装说明：<br> </p><p>将压缩包中的以下文件夹和文件解压至 Mod Organizer 2/plugins 文件夹：</p> <ul> <li>/data</li><li><a href="http://pySyncModOrder.py">pySyncModOrder.py</a></li><li><a href="http://pyMergePluginsHide.py">pyMergePluginsHide.py</a></li></ul> <blockquote> <p>当需要更新Mod Organizer 2时，将新版压缩包解压到Mod Organizer 2文件夹中，并在出现提示时覆盖。按照上述说明以管理员身份运行程序，重新下载并安装MO2插件。</p> </blockquote> <p>五、汉化安装<br> </p><p>首先将下载好的汉化补丁放入游戏根目录<br> </p><p><a href="https://pan.baidu.com/s/1vM49TqGgIznUgxSmqdw6dw">https://pan.baidu.com/s/1vM49TqGgIznUgxSmqdw6dw</a> 提取码: ecdg<br> </p><p>双击汉化补丁进行安装，一路点击下一步，在 选择组件 界面停下，反选所有选项，也就是只选择 汉化必须文件<br> </p><p>点击下一步进行安装(<strong>请注意目标位置是否为游戏所在目录</strong>)，安装完成后在最后界面选择 运行FNVTools设置游戏 ，结束后自动弹出FNVTools2.1<br> </p><p>点击FNVTools中的 INI设置和优化 ，进入INI设置和优化后根据下图进行设置<br> </p><p><img title="fnvtools_pic" alt="fnvtools_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/fnvtools_pic.JPG?raw=true"> </p><ul> <li>首先勾选 1 前面的框，然后根据CPU线程数调整后面的数字，可以导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li><li>然后勾选 2 所有的框 ， <strong>保持 3 中的三个数字为默认</strong> (下面的优化会涉及此项)</li><li>在 切换INI 字体设置 一栏选择想要的字体(中文幼圆大字 和 中文宋体小字 二选一)，点击后弹出 疑问 对话框，选择 是，再点击确定。最后点击最下方的 保存 ，然后关闭 FNVTools2.1。</li></ul> <p>为exe文件添加排除数据执行保护：<br> </p><p>右键单击 此电脑 ，选择 属性 ，在左边一栏选择 高级系统设置 ，在 性能 一栏下点击 设置 ，切换到 数据执行保护选项卡，选择 为除下列选定程序之外的所有程序和服务启用DEP ，点击 添加 ，在弹出的框中导航到游戏根目录，双击添加 FalloutNV.exe ，同理继续添加 FalloutNVLauncher.exe 。完成添加后点击 应用 ，然后点击 确定 ，退出所有窗口。如果系统要求重新启动，手动重启即可。</p> <p>此时汉化已完成，Steam版可以直接双击FalloutNV.exe进入游戏，GOG版本需要下载破解的steam_api.dll放入根目录才能进入游戏。</p> <blockquote> <p>汉化补丁替换了FalloutNV.exe，并且替换的exe来自Steam版。而GOG版与Steam版最大的区别是GOG版对exe文件进行了优化。所以如果想玩中文版的话建议直接买Steam版。</p> </blockquote> <p>进入游戏，主界面和菜单应该都显示汉化。<strong>点击 选项-显示 ，滚轮滑倒最下，将 一般字幕 设置为开启。</strong>然后退到主菜单，开始新游戏测试游戏内容及汉化是否有问题。</p> <p>六、Mod Organizer 2配置及INI优化<br> </p><p>1.配置Mod Organizer 2：<br> </p><p>运行ModOrganizer.exe<br> </p><p>从名为 Choose Instance 的弹出窗口中，选择 Portable<br> </p><p>从弹出窗口 Please select the game to manage，选择 New Vegas<br> </p><p>如果未显示New Vegas选项，请选择 Browse…，然后导航到根文件夹并选择FalloutNV.exe<br> </p><p>如果有一个名为 INI file is read-only 的窗口，请选择 Yes<br> </p><p>从弹出窗口 Show Tutorial?，选择 No<br> </p><p>从弹出窗口 Register?，选择 Yes<br> </p><p>进入主界面<br> </p><p>点击顶部的按钮<img title="setting_pic" alt="setting_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true">，在 General 选项卡下第一栏 Language 项选择 Chinese (simplified)<br> </p><p>点击 OK 软件切换成中文<br> </p><p>如果未选中右栏中的所有插件，请右键单击右栏空白处并选择 全部启用<br> </p><p>按照下图中的顺序改变左栏和右栏中的加载顺序<br> </p><p><img title="order_pic" alt="order_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/order_pic.jpg?raw=true"> </p><ul> <li>如果您的游戏是GOG版本，则加载顺序中可能存在FalloutNV_lang.esp ，请导航到/Data文件夹并将其删除</li></ul> <p>单击MO2顶部栏上的按钮<img title="setting_pic" alt="setting_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2setting_pic.jpg?raw=true">，导航到” 路径”选项卡<br> </p><p>如果您使用SSD或空间很小的HDD，请将 下载 路径设置为具有足够空间的某个位置<br> </p><p>以下选项只在你有Nexus账户时才设置，没有的可以跳过</p> <ul> <li>在 N网 选项卡中，单击 Connect to Nexus ，MO2应在浏览器中打开Nexus页面</li><li>选择 Authorise</li><li>等待页面提示 You have successfully logged into Mod Organizer 2! 后退出浏览器</li></ul> <p>点击 OK 退出MO2中的设置菜单，如果MO2提示你重启，你应该选择 Yes</p> <p>2.在Mod Organizer 2中创建新配置文件：<br> </p><p>Mod Organizer 2的配置文件功能允许在不同的mod配置之间轻松切换，可以通过左栏上方的下拉菜单选择配置文件。<br> </p><p>单击MO2顶部栏上的按钮<img title="profile_pic" alt="profile_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2profile_pic.jpg?raw=true"><br> </p><p>单击Default配置文件，然后选择重命名<br> </p><p>输入Vanilla作为新名称<br> </p><p>选中 Vanilla 配置文件，选择复制<br> </p><p>输入Core作为新名称，然后单击 OK<br> </p><p>选择 Core 配置文件并选中下方的 使用特定的ini (第二项) 和 自动档案无效化<br> </p><p>关闭配置文件窗口，可能会报错提示缺少ini文件，点击 OK 即可</p> <p>3.调整FalloutCustom.ini：<br> </p><p>确保目前选择的配置文件为 Core<br> </p><p>单击MO2顶部栏上的按钮<img title="inieditor_pic" alt="inieditor_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true"> ，然后选择 INI编辑器<br> </p><p>导航到 falloutcustom.ini 选项卡，该选项卡应为空白<br> </p><p>将以下内容粘贴到框中：<br> </p><p>[General]<br> </p><p>bUseThreadedAI=1<br> </p><p>INumHWThreads=4<br> </p><p>bPreemptivelyUnloadCells=1</p> <p>[BackgroundLoad]<br> </p><p>bBackgroundCellLoads=1<br> </p><p>bSelectivePurgeUnusedOnFastTravel=1</p> <p>[Display]<br> </p><p>fLightLODDefaultStartFade=10240.0<br> </p><p>fLightLODRange=10240.0<br> </p><p>fLightLODMinStartFade=10240.0<br> </p><p>fLightLODMaxStartFade=10240.0<br> </p><p>fShadowLODDefaultStartFade=200.0<br> </p><p>fShadowLODRange=200.0<br> </p><p>fShadowLODMinStartFade=100.0<br> </p><p>fShadowLODMaxStartFade=1000.0<br> </p><p>fSpecularLODDefaultStartFade=10240.0<br> </p><p>fSpecularLODRange=10240.0<br> </p><p>fSpecularLODMinStartFade=10240.0<br> </p><p>fSpecularLODMaxStartFade=10240.0<br> </p><p>iPresentInterval=0</p> <p>[Controls]<br> </p><p>fForegroundMouseAccelBase=0<br> </p><p>fForegroundMouseAccelTop=0<br> </p><p>fForegroundMouseBase=0<br> </p><p>fForegroundMouseMult=0<br> </p><p>fXenonVertLookSpeed=1200.0000<br> </p><p>fXenonHorizLookSpeed=1500.0000</p> <p>[Grass]<br> </p><p>fGrassStartFadeDistance=17000</p> <p>[Audio]<br> </p><p>iAudioCacheSize=8192<br> </p><p>iMaxSizeForCachedSound=2048</p> <ul> <li>将INumHWThreads更改为CPU所具有的线程数，可以导航到 <em>文档/My Games/FalloutNV</em> 打开 RendererInfo.txt ，参考最后一行 HW Thread Count 后面的数字</li><li>如果你不以16：9的宽高比运行游戏，可以删除<br><br>fXenonVertLookSpeed=1200.0000<br><br>fXenonHorizLookSpeed=1500.0000</li></ul> <p>完成后点击 保存 ，然后关闭INI编辑器。</p> <p>七、BethINI<br> </p><p>BethINI相当于一个第三方的启动器，可以更改画质及其他选项，并对INI进行优化。<br><br><a href="https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw">https://pan.baidu.com/s/1cCRsTZf1S-ekJAIoajRhYw</a> 提取码: jw7j</p> <p>注意事项：<br><br>BethINI standalone容易被防病毒软件标记为误报，所以最好请其添加到将杀毒软件的白名单中。<strong>请注意，不要通过Mod Organizer 2运行，也不要在Mod Organizer 2打开时运行BethINI。</strong></p> <p>安装使用说明：</p> <ol> <li>运行前请确保已运行过FalloutNVLauncher.exe并生成了相应的INI文件</li><li><strong>请确保Mod Organizer 2关闭</strong>，解压缩文件到 <em>/Fallout NV Modding/Tools</em> 文件夹，进入并运行BethINI.exe</li><li>在弹出的窗口中下拉选择 Fallout New Vegas ，等待进入程序。</li><li>进入程序后导航到 Setup 选项卡， <strong>取消选择</strong>下方的全部选项方框。之后在 Mod Organizer 一栏下拉菜单中选择 Browse ,在弹出的框中导航到 Mod Organizer 2 文件夹并双击选择 ModOrganizer.exe</li><li>在 INI Path 一栏下拉菜单中选择您现在使用的Mod Organizer 2配置文件，如 ModOrganizer&gt;Core 。在弹出对话框中选择 确定 。此时会弹出对话框提示BethINI要重新启动，点击 确定 。重启后会弹出名为 Modify Custom INIs? 对话框， <strong>此时选择 否</strong> 。重新进入BethINI后导航到 Setup 选项卡，请确保全部5个选择框都没有选择。</li><li>导航到 Basic 选项卡，在 Presets 栏中选择 BethINI Presets ，再选择 Recommended Tweaks ，程序会自动优化相应的INI文件，之后请根据配置在 Poor 到 Ultra 中选择合适的画质选项。</li><li>选择完画质后在 Display 一栏中选择合适的分辨率，如果没有需要的分辨率则可以手动输入。可以自行选择 Antialiasing 和 Anisotropic Filtering 倍数。最后选择最下方的 Enable File Selection (如果已经选择则不用管)，确定一切选择正确后点击 Save and Exit 退出。</li></ol> <p><strong>在使用了BethINI之后，请不要再运行FalloutNVLauncher.exe，也不要在Steam中启动新维加斯。如果在以后的游戏流程中需要修改画质及其他选项，请阅读指南最后有关BethINI的说明。</strong></p> <p>八、重要前置<br><br>曾经很流行的前置 NVSR 和 Zan AutoPurge Crash Protector 已经废弃，这两个插件会对游戏稳定性产生负面影响。<br><br>NVSE<br><br><a href="http://nvse.silverlock.org/">http://nvse.silverlock.org/</a><br><br>特别安装说明：<br><br>单击 Download (stable version 5.1b4) 旁边的链接进行下载<br><br>将压缩包内 nvse_5_1_beta4 文件夹中的所有内容解压到根目录<br> </p><ul> <li>扩展引擎的脚本功能，新维加斯最基础的前置，手动安装：<br></li></ul> <p>前置补丁包<br> </p><p>特别安装说明：<br><br>单击 Download (stable version 5.1b4) 旁边的链接进行下载<br><br>将压缩包内 nvse_5_1_beta4 文件夹中的所有内容解压到根目录<br> </p><ul> <li>个人制作的前置补丁包，通过Mod Organizer2安装。<br></li></ul> <blockquote> <p>补丁包中含有的Mod及说明，参见<a href="https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md">https://github.com/feelbetterhua/nvguideline_cn/blob/master/mod_introduction.md</a><br> </p></blockquote> <p>4GBpatch<br> </p><p><a href="https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA">https://pan.baidu.com/s/1J5aaQVnJIml1V0YfL-teUA</a> 提取码: bj3h<br> </p><p>特殊安装说明：<br> </p><p>将压缩包内的 4gb_patch.exe 解压到根目录<br> </p><p>请确保 <strong>没有</strong>运行Mod Organizer 2，导航到根目录，右键单击 4gb_patch.exe ，选择 以管理员身份运行<br> </p><p>在弹出的窗口中双击选择 nvse_loader.exe ，应该弹出窗口显示 Executable successfully patched！<br> </p><p>此时点击 Another File ，在弹出的窗口双击选择 FalloutNV.exe ，之后点击 OK 退出。</p> <ul> <li>使游戏能够识别大地址，这意味着它可以使用4GB RAM而不是2GB</li></ul> <p><strong>验证NVSE和4GBpatch是否运行：</strong><br> </p><p>打开Mod Organizer 2，在右栏上方的下拉菜单选择 NVSE ，点击运行<br> </p><p>进入游戏主菜单后，按 ~ 键打开控制台<br> </p><p>将getnvseversion输入控制台并按Enter键<br> </p><p>控制台应报告 NVSE version: 5</p> <ul> <li>如果没有，请检查NVSE是否已正确安装并重试</li></ul> <p>将getislaa输入控制台并按Enter键<br> </p><p>控制台应该报告 GetisLAA &gt;&gt; 2.0000</p> <ul> <li>如果控制台报告 GetisLAA &gt;&gt; 0.0000，则说明补丁未正确安装</li><li>如果控制台报告 GetisLAA &gt;&gt; 1.0000，则修补程序已正确安装但无法正常运行，尝试以管理员身份运行</li><li>如果控制台报告错误消息，则表示您未正确安装JIP LN NVSE</li></ul> <p><strong>验证完成，之后都在Mod Organizer 2中通过NVSE进行游戏</strong></p> <blockquote> <p>通过Steam或GOG验证您的游戏文件都将撤消补丁</p> </blockquote> <p>九、显示设置<br> </p><p><strong>仅适用于具有NVIDIA GPU的用户：NVIDIA Profile Inspector</strong><br> </p><p><a href="https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA">https://pan.baidu.com/s/1Wk-h1BotfcNWK2SBaqm9UA</a> 提取码: qwfa<br> </p><p>特别安装说明：<br> </p><p>将压缩包解压到根目录以外的安全位置<br> </p><p>运行 NVidiaProfileInspectorDmWPortable.exe<br> </p><p>如果有弹出窗口，请单击是<br> </p><p>从左上角的Profiles：下拉列表中，选择Fallout - New Vegas<br> </p><p>在 2. - Sync and Refresh 部分中，更改以下内容：</p> <ul> <li>Frame Rate Limiter - 58 FPS</li><li>Maximum pre-rendered frames - 1</li><li>Vertical Sync - Force on</li></ul> <p>如果您使用G-Sync或Freesync，请不要启用 Vertical Sync<br> </p><p>在5. - Common部分中，更改以下内容：</p> <ul> <li>Power management mode - Prefer maximum performance</li></ul> <p>单击右上角的 Apply changes 按钮，然后退出</p> <p><strong>仅适用于使用AMD GPU的用户：调整AMD Radeon设置</strong><br> </p><p>(注：本人使用NVIDIA GPU，这一步没有亲自验证，翻译仅供参考)<br> </p><p>右键单击桌面并选择AMD Radeon Settings<br> </p><p>在” 游戏”选项卡中，选择 Fallout New Vegas 配置文件<br> </p><p>在” 配置文件图形”选项卡中，更改以下内容<br> </p><p>等待垂直刷新 - 增强同步<br> </p><p>如果不能选择增强型同步，请选择始终开启<br> </p><p>如果使用Freesync，请不要启用等待垂直刷新<br> </p><p>启用 冷却（FPS）<br> </p><p>将Chill Min和Chill Max设置为58<br> </p><p>点击左下角的主页按钮（设置应自动保存），并确保在配置文件名称下方显示”已启用 “字样<br> </p><p>如果没有，请单击配置文件名称右侧的三个垂直点，然后选择启用配置文件</p> <blockquote> <p>关于限制FPS的注意事项:由于Gamebryo的物理特性与帧速率相关，因此FPS 必须上限为60或更低。该指南使用58FPS，因为如果不使用V-Sync，它应该可以防止屏幕撕裂</p> </blockquote> <p>伪全屏设置：<br> </p><p>该步骤可以使你的游戏运行在窗口模式下，此时切入切出窗口应该不会再卡死，但游戏帧数可能会降低，请根据自己的需要选择是否设置。<br> </p><p>方法一：<br> </p><p>确保已安装前置 New Vegas Reloaded - NVGE<br> </p><p>单击MO2顶部栏上的按钮<img title="inieditor_pic" alt="inieditor_pic" src="https://github.com/feelbetterhua/nvguideline_cn/blob/master/MO2inieditor_pic.jpg?raw=true"> ，然后选择 INI编辑器<br> </p><p>导航到 falloutcustom.ini 选项卡<br> </p><p>在 [Display] 部分下添加以下内容</p> <ul> <li>bFull Screen=0</li></ul> <blockquote> <p>有些用户报告此调整需要在 FalloutPrefs.ini 选项卡中进行</p> </blockquote> <p>如果此方法不起作用，则使用方法二 OneTweak：<br> </p><p><a href="https://pan.baidu.com/s/1eG1u8EUhVW9Ri6nPDf4Ezg">https://pan.baidu.com/s/1eG1u8EUhVW9Ri6nPDf4Ezg</a> 提取码: m3b3<br> </p><p>要安装的文件：<br> </p><p>将压缩包内的 plugins 文件夹解压到 Fallout New Vegas/Data/nvse/</p> <p>十、最终测试<br> </p><p>至此基础游戏的设置及优化已全部完成，请按照以下步骤进行测试：<br> </p><p>通过MO2运行游戏<br> </p><p>启动一个新存档，快速通过Doc Mitchell所在的教程<br> </p><p>离开医生的房间后，打开pipboy检查各个选项是否有问题<br> </p><p>在游戏中花费至少20-30分钟做任何事情以确保游戏顺利进行</p> <ul> <li>如果你按照本指南完整做到了每一个步骤，并选择了合适的画质与分辨率，此时你的游戏应没有卡顿并可以长时间运行不跳出。</li><li>如果你有任何问题，尝试先判断是否完全按本指南进行安装设置。如果确定步骤没有问题，请先调低画质及分辨率再进行测试(但尽量不要以最低画质运行)。</li><li>如果问题依旧存在，可以回复进行询问，我尽可能回答。</li></ul> <p>以上是本指南的全部内容，欢迎各位回复讨论问题或补充方法。如果你在阅读或使用完本指南后觉得不错，可以帮忙扩散本指南，让更多的人享受到丝滑流畅的新维加斯体验。</p> <hr> <p>有关BethINI的说明：<br> </p><p>BethINI相当于一个第三方的FalloutNVLauncher，但拥有更好的预设及更多的选项，它们的共同点是都通过修改INI文件来工作。而Mod Organizer 2会为每一个配置文件单独创建”虚拟”的INI文件，这时FalloutNVLauncher修改原生INI文件就对从MO2中启动的游戏不起作用。<br> </p><p>通过将BethINI与Mod Organizer 2链接，BethINI可以直接管理MO2中某个配置文件的INI，不再修改原生INI。 <strong>所以今后的游戏过程中如需改变画质就直接使用BethINI，只要确保选择了正确的MO2配置文件即可(一定不要同时运行BethINI和MO2)。</strong></p> <p>有关ENB与NVGE的说明：<br> </p><p>使用4GBpatch时正常安装ENB，如果你在使用NVGE-New Vegas Reload的同时使用ENB，请打开根目录下的 enblocal.ini 并将其中的 SpeedHack=true 改为 SpeedHack=false ，以保证两者相互兼容。<br> </p><p>NVGE自带截图功能，并且截图不包含UI，快捷键是F11。如需带UI截图，可以按 PrtScr 键截取。NVGE的截图保存在根目录下的 Screenshots 文件夹，带UI的截图保存在游戏根目录。</p> </body> </html>
