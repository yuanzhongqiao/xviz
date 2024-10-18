<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="35069658" _msthash="319">XVIZ （小维兹）</h1><a id="user-content-xviz" class="anchor" aria-label="永久链接：XVIZ" href="#xviz" _mstaria-label="227708" _msthash="320"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://coveralls.io/github/uber/xviz?branch=master" rel="nofollow"><img src="https://camo.githubusercontent.com/75ee8e3521a501e817e0823710c86c9afdd955b021c52d512bc8a36f3822a8e6/68747470733a2f2f636f766572616c6c732e696f2f7265706f732f6769746875622f756265722f7876697a2f62616467652e7376673f6272616e63683d6d6173746572" alt="覆盖状态" data-canonical-src="https://coveralls.io/repos/github/uber/xviz/badge.svg?branch=master" style="max-width: 100%;" _mstalt="259493" _msthash="321"></a></p>
<p dir="auto" _msttexthash="318933992" _msthash="322">XVIZ 是一种用于实时传输和可视化自主数据的协议。在<a href="http://avs.auto/#/xviz" rel="nofollow" _istranslated="1">文档和规范</a>中了解更多信息。</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/aurora-opensource/xviz/blob/master/docs/overview/images/high-level.png"><img src="https://github.com/aurora-opensource/xviz/raw/master/docs/overview/images/high-level.png" alt="高级概述" style="max-width: 100%;" _mstalt="347165" _msthash="323"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13834964" _msthash="324">工具和示例</h2><a id="user-content-tools-and-examples" class="anchor" aria-label="永久链接：工具和示例" href="#tools-and-examples" _mstaria-label="689962" _msthash="325"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="54379351" _msthash="326">此存储库包含以下子模块：</p>
<ul dir="auto">
<li><code>@xviz/builder</code><font _mstmutation="1" _msttexthash="132014272" _msthash="327">- Node.js 用于将数据转换为 XVIZ 协议的实用程序。</font></li>
<li><code>@xviz/cli</code><font _mstmutation="1" _msttexthash="57035862" _msthash="328">- 用于 XVIZ 协议的 CLI 实用程序。</font></li>
<li><code>@xviz/io</code><font _mstmutation="1" _msttexthash="79116804" _msthash="329">- 用于加载、访问和操作 XVIZ 数据的库。</font></li>
<li><code>@xviz/parser</code><font _mstmutation="1" _msttexthash="114343138" _msthash="330">- 用于使用 XVIZ 数据的客户端解码器和同步器。</font></li>
<li><code>@xviz/schema</code><font _mstmutation="1" _msttexthash="50831183" _msthash="331">- XVIZ 协议的验证和架构。</font></li>
<li><code>@xviz/server</code><font _mstmutation="1" _msttexthash="84225726" _msthash="332">- 支持完整 XVIZ 协议的完整服务器模块。</font></li>
</ul>
<p dir="auto" _msttexthash="15312128" _msthash="333">和例子：</p>
<ul dir="auto">
<li _msttexthash="124286721" _msthash="334">将 <a href="http://www.cvlibs.net/datasets/kitti/raw_data.php" rel="nofollow" _istranslated="1">KITTI</a> 和 <a href="https://nuscenes.org" rel="nofollow" _istranslated="1">Nutonomy</a> 等开放数据集转换为
XVIZ 协议。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11905335" _msthash="335">快速开始</h2><a id="user-content-quick-start" class="anchor" aria-label="永久链接： 快速入门" href="#quick-start" _mstaria-label="446966" _msthash="336"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="66144312" _msthash="337">您需要 <a href="https://nodejs.org/en/" rel="nofollow" _istranslated="1">Node.js</a> 和 <a href="https://yarnpkg.com/lang/en/docs/install" rel="nofollow" _istranslated="1">yarn</a> 来
运行示例。</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Clone XVIZ</span>
$ git clone https://github.com/uber/xviz.git
$ <span class="pl-c1">cd</span> xviz

<span class="pl-c"><span class="pl-c">#</span> Install dependencies</span>
$ yarn bootstrap</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto" _msttexthash="57310448" _msthash="338">转换和提供 KITTI 示例数据：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Download KITTI data</span>
$ ./scripts/download-kitti-data.sh

<span class="pl-c"><span class="pl-c">#</span> Convert KITTI data if necessary and run the XVIZ Server and Client</span>
$ ./scripts/run-kitti-example.sh</pre><div class="zeroclipboard-container">
   
     
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="8097843" _msthash="339">NPM 脚本</h2><a id="user-content-npm-scripts" class="anchor" aria-label="永久链接：NPM 脚本" href="#npm-scripts" _mstaria-label="425802" _msthash="340"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><code>bootstrap</code><font _mstmutation="1" _msttexthash="20450352" _msthash="341">- 安装依赖项</font></li>
<li><code>build</code><font _mstmutation="1" _msttexthash="31539729" _msthash="342">- 重新构建所有模块</font></li>
<li><code>test</code><font _mstmutation="1" _msttexthash="191174698" _msthash="343">- 运行完整测试（lint、Node 中的单元测试和无头浏览器）</font></li>
<li><code>test bench</code><font _mstmutation="1" _msttexthash="26589251" _msthash="344">| - 运行基准测试</font><code>bench</code></li>
<li><code>test bench-browser</code><font _mstmutation="1" _msttexthash="52347269" _msthash="345">- 在浏览器中运行基准测试</font></li>
<li><code>test node</code><font _mstmutation="1" _msttexthash="43688476" _msthash="346">- 在 Node 中运行单元测试</font></li>
<li><code>test browser</code><font _mstmutation="1" _msttexthash="41943031" _msthash="347">- 在浏览器中运行测试</font></li>
<li><code>test browser-headless</code><font _mstmutation="1" _msttexthash="67127723" _msthash="348">- 在 Headless 浏览器中运行测试</font></li>
<li><code>lint</code><font _mstmutation="1" _msttexthash="7981142" _msthash="349">- 运行 lint</font></li>
<li><code>lint fix</code><font _mstmutation="1" _msttexthash="8065174" _msthash="350">- 运行 Prettier</font></li>
<li><code>publish beta</code><font _mstmutation="1" _msttexthash="10433566" _msthash="351">- 发布 Beta 版</font></li>
<li><code>publish prod</code><font _mstmutation="1" _msttexthash="20856121" _msthash="352">- 发布生产版本</font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="12431042" _msthash="353">供款要求</h2><a id="user-content-requirements-for-contribution" class="anchor" aria-label="永久链接： 贡献要求" href="#requirements-for-contribution" _mstaria-label="1279395" _msthash="354"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="81515551" _msthash="355">pre-commit 钩子要求你已安装：</font><code>yarn test-fast</code><code>jq</code></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>brew install jq
</code></pre><div class="zeroclipboard-container">
   
  </div></div>
</article></div>
