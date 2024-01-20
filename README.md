<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div id="user-content-top" align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer" href="/evidence-dev/evidence/blob/main/sites/docs/static/img/wordmark.svg"><img src="/evidence-dev/evidence/raw/main/sites/docs/static/img/wordmark.svg" alt="证据标志" width="100%" style="max-width: 100%;"></a>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商业智能即代码：使用 SQL 和 Markdown 生成报告</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-docs--examples--cloud--slack" class="anchor" aria-hidden="true" tabindex="-1" href="#docs--examples--cloud--slack"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><a href="https://docs.evidence.dev" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://evidence.dev/examples" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://evidence.dev/cloud" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">云</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">| </font></font><a href="https://slack.evidence.dev" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">松弛</font></font></a></h3>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d19b7a1e92f84ebe2ade180343e3c8641aa1b37e5d7eb3402d7254024450366a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f65766964656e63652d6465762f65766964656e63653f7374796c653d736f6369616c"><img src="https://camo.githubusercontent.com/d19b7a1e92f84ebe2ade180343e3c8641aa1b37e5d7eb3402d7254024450366a/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f65766964656e63652d6465762f65766964656e63653f7374796c653d736f6369616c" alt="GitHub 存储库星星" data-canonical-src="https://img.shields.io/github/stars/evidence-dev/evidence?style=social" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/1e79cb18813f56392813d0663807c1953f6ec383893d2adfd7966afa8e11f062/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f6c2f25343065766964656e63652d64657625324665766964656e6365"><img src="https://camo.githubusercontent.com/1e79cb18813f56392813d0663807c1953f6ec383893d2adfd7966afa8e11f062/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f6c2f25343065766964656e63652d64657625324665766964656e6365" alt="国家公共管理" data-canonical-src="https://img.shields.io/npm/l/%40evidence-dev%2Fevidence" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/4a105aeb6c9aeb7cf8486c3669751089b131dee56fccd4fe978f22f7bf652992/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f4065766964656e63652d6465762f65766964656e63653f6c6f676f3d6e706d"><img src="https://camo.githubusercontent.com/4a105aeb6c9aeb7cf8486c3669751089b131dee56fccd4fe978f22f7bf652992/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f4065766964656e63652d6465762f65766964656e63653f6c6f676f3d6e706d" alt="新项目管理" data-canonical-src="https://img.shields.io/npm/v/@evidence-dev/evidence?logo=npm" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d3b3f891d9c29b840ccc03a15b8362442a465d894c2f02655de9efe36135f002/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f616374696f6e732f776f726b666c6f772f7374617475732f65766964656e63652d6465762f65766964656e63652f72656c656173652e796d6c3f6c6f676f3d6e706d"><img src="https://camo.githubusercontent.com/d3b3f891d9c29b840ccc03a15b8362442a465d894c2f02655de9efe36135f002/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f616374696f6e732f776f726b666c6f772f7374617475732f65766964656e63652d6465762f65766964656e63652f72656c656173652e796d6c3f6c6f676f3d6e706d" alt="发布" data-canonical-src="https://img.shields.io/github/actions/workflow/status/evidence-dev/evidence/release.yml?logo=npm" style="max-width: 100%;"></a>
<a href="https://slack.evidence.dev" rel="nofollow"><img src="https://camo.githubusercontent.com/6346d60a5578fa968ab30091c5f66cb2706a8cc5097d7735cc9d1f677f7eb5ee/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f736c61636b2d6a6f696e2d626c75653f6c6f676f3d736c61636b26616d70" alt="加入松弛" data-canonical-src="https://img.shields.io/badge/slack-join-blue?logo=slack&amp;amp" style="max-width: 100%;"></a></p>
</div>
<h1 tabindex="-1" dir="auto"><a id="user-content-how-it-works" class="anchor" aria-hidden="true" tabindex="-1" href="#how-it-works"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么运行的</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Evidence 是一种开源、基于代码的拖放式商业智能工具替代方案。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/evidence-dev/evidence/blob/main/sites/docs/static/img/how-it-works.png"><img src="/evidence-dev/evidence/raw/main/sites/docs/static/img/how-it-works.png" alt="怎么运行的" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Evidence 从 Markdown 文件生成一个网站：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Markdown 文件中的SQL 语句</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对数据源运行查询</font></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用这些查询结果呈现</font><strong><font style="vertical-align: inherit;">图表和组件</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模板化页面</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从单个 Markdown 模板生成许多页面</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">循环</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">If / Else</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语句允许控制向用户显示的内容</font></font></li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-install" class="anchor" aria-hidden="true" tabindex="-1" href="#install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h1>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font><a href="https://marketplace.visualstudio.com/items?itemName=Evidence.evidence-vscode" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">证据 VSCode 扩展</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开命令面板 (F1) 并输入</font></font><code>Evidence: New Evidence Project</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击底部状态栏中的“开始取证”按钮</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅文档了解</font></font><a href="https://docs.evidence.dev/getting-started/install-evidence" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他安装选项</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（CLI、Docker 等）</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-publish" class="anchor" aria-hidden="true" tabindex="-1" href="#publish"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布</font></font></h1>
<ul dir="auto">
<li><a href="https://evidence.dev/cloud" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Evidence Cloud</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是安全托管项目的最简单方法。</font><font style="vertical-align: inherit;">开始使用是免费的。</font></font></li>
<li><a href="https://docs.evidence.dev/deployment/overview" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自托管</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项包括 Netlify、Vercel、您自己的基础设施和其他静态站点托管平台。</font></font></li>
</ul>
<h1 tabindex="-1" dir="auto"><a id="user-content-join-the-evidence-community" class="anchor" aria-hidden="true" tabindex="-1" href="#join-the-evidence-community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入证据社区</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入我们的</font></font><a href="https://slack.evidence.dev" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack 频道</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，参与社区讨论、分享您正在处理的内容或请求功能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://twitter.com/evidence_dev" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在Twitter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上关注我们</font><font style="vertical-align: inherit;">，以获取有关 Evidence 的最新更新。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有兴趣做出贡献，请加入我们的</font></font><a href="https://slack.evidence.dev" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack 频道</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、提出</font></font><a href="https://github.com/evidence-dev/evidence/issues/new"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或贡献拉取请求。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">证据已获得麻省理工学院许可。</font><font style="vertical-align: inherit;">有关许可信息，请参阅</font></font><a href="/evidence-dev/evidence/blob/main/LICENSE.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LICENSE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font></font></p>
</article></div>
