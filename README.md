<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记</font></font></h1><a id="user-content-marker" class="anchor" aria-label="永久链接：标记" href="#marker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Marker 快速准确地将 PDF 转换为 markdown。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持多种文档（针对书籍和科学论文进行了优化）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持所有语言</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">删除页眉/页脚/其他物品</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格式化表格和代码块</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提取并保存图像和 Markdown</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将大多数方程式转换为乳胶</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 GPU、CPU 或 MPS</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么运行的</font></font></h2><a id="user-content-how-it-works" class="anchor" aria-label="永久链接：工作原理" href="#how-it-works"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Marker 是深度学习模型的管道：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提取文本，必要时进行 OCR（启发式、</font></font><a href="https://github.com/VikParuchuri/surya"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">surya</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、tesseract）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检测页面布局并找到阅读顺序（</font></font><a href="https://github.com/VikParuchuri/surya"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">surya</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">清理并格式化每个块（启发式、</font></font><a href="https://github.com/VikParuchuri/texify"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">texify</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组合块并对完整文本进行后处理（启发式，</font></font><a href="https://huggingface.co/vikp/pdf_postprocessor_t5" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pdf_postprocessor</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它仅在必要时使用模型，从而提高速度和准确性。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></h2><a id="user-content-examples" class="anchor" aria-label="永久链接：示例" href="#examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PDF</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">牛轧糖</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://greenteapress.com/thinkpython/thinkpython.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">思考 Python</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教科书</font></font></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/marker/thinkpython.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/nougat/thinkpython.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
</tr>
<tr>
<td><a href="https://greenteapress.com/thinkos/thinkos.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">思考操作系统</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教科书</font></font></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/marker/thinkos.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/nougat/thinkos.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
</tr>
<tr>
<td><a href="https://arxiv.org/pdf/2101.03961.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关变压器</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">arXiv 论文</font></font></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/marker/switch_transformers.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/nougat/switch_transformers.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
</tr>
<tr>
<td><a href="https://arxiv.org/pdf/1804.07821.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多列 CNN</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">arXiv 论文</font></font></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/marker/multicolcnn.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
<td><a href="https://github.com/VikParuchuri/marker/blob/master/data/examples/nougat/multicolcnn.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">看法</font></font></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表现</font></font></h2><a id="user-content-performance" class="anchor" aria-label="固定链接：性能" href="#performance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/VikParuchuri/marker/blob/master/data/images/overall.png"><img src="/VikParuchuri/marker/raw/master/data/images/overall.png" alt="总体基准" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上述结果是使用标记和牛轧糖设置得到的，因此它们各自在 A6000 上占用约 4GB 的 VRAM。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#benchmarks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下文的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详细速度和准确性基准，以及如何运行您自己的基准的说明。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商业用途</font></font></h1><a id="user-content-commercial-usage" class="anchor" aria-label="永久链接：商业用途" href="#commercial-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我希望标记尽可能广泛地普及，同时仍能为我的开发/培训费用提供资金。研究和个人使用始终是可以的，但商业使用会受到一些限制。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些模型的权重是经过授权的</font></font><code>cc-by-nc-sa-4.0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但对于最近 12 个月内总收入低于 500 万美元且一生中筹集的 VC/天使资金低于 500 万美元的任何组织，我将免除该授权。如果您想删除 GPL 许可要求（双重许可）和/或在收入限制之外将权重用于商业用途，请查看</font></font><a href="https://www.datalab.to" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">托管 API</font></font></h1><a id="user-content-hosted-api" class="anchor" aria-label="永久链接：托管 API" href="#hosted-api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.datalab.to/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有可用的标记托管 API </font><font style="vertical-align: inherit;">。它目前处于测试阶段，我正在努力优化速度。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></h1><a id="user-content-community" class="anchor" aria-label="固定链接：社区" href="#community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://discord.gg//KuZwXNGnfH" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是我们讨论未来发展的地方。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">限制</font></font></h1><a id="user-content-limitations" class="anchor" aria-label="固定链接：限制" href="#limitations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PDF 是一种棘手的格式，因此标记并不总是能完美地工作。以下是一些已知的限制，这些限制正在规划中：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Marker 不会将 100% 的方程式转换为 LaTeX。这是因为它必须先检测然后转换。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表格的格式并不总是 100% 正确 - 文本可能位于错误的列中。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">空格和缩进并不总是受到尊重。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并非所有的线/跨度都能正确连接。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此功能最适合不需要大量 OCR 的数字 PDF。它针对速度进行了优化，并使用有限的 OCR 来修复错误。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h1><a id="user-content-installation" class="anchor" aria-label="固定链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您需要 Python 3.9+ 和 PyTorch。如果您使用的不是 Mac 或 GPU 机器，则可能需要先安装 CPU 版本的 torch。请参阅</font></font><a href="https://pytorch.org/get-started/locally/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装方式：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install marker-pdf</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install marker-pdf" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可选：OCRMyPDF</font></font></h2><a id="user-content-optional-ocrmypdf" class="anchor" aria-label="永久链接：可选：OCRMyPDF" href="#optional-ocrmypdf"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅当您想使用可选的</font></font><code>ocrmypdf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ocr 后端时才需要。请注意，它</font></font><code>ocrmypdf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含 Ghostscript（AGPL 依赖项），但通过 CLI 调用它，因此它不会触发许可证条款。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><a href="/VikParuchuri/marker/blob/master/docs/install_ocrmypdf.md"><font style="vertical-align: inherit;">请参阅此处的</font></a><font style="vertical-align: inherit;">说明</font></font><a href="/VikParuchuri/marker/blob/master/docs/install_ocrmypdf.md"><font style="vertical-align: inherit;"></font></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h1><a id="user-content-usage" class="anchor" aria-label="固定链接：用法" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，一些配置：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查中的设置</font></font><code>marker/settings.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您可以使用环境变量覆盖任何设置。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的手电筒设备将被自动检测，但您可以覆盖此设置。例如，</font></font><code>TORCH_DEVICE=cuda</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果使用 GPU，请设置</font></font><code>INFERENCE_RAM</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 GPU VRAM（每个 GPU）。例如，如果您有 16 GB 的 VRAM，请设置</font></font><code>INFERENCE_RAM=16</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据文档类型，marker 每个任务的平均内存使用量可能会略有不同。</font></font><code>VRAM_PER_TASK</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现任务因 GPU 内存不足错误而失败，您可以配置来调整此值。</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，marker 将用于</font></font><code>surya</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OCR。Surya 在 CPU 上的速度较慢，但&ZeroWidthSpace;&ZeroWidthSpace;比 tesseract 更准确。如果您想要更快的 OCR，请设置</font></font><code>OCR_ENGINE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>ocrmypdf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这还需要外部依赖项（见上文）。如果您根本不想要 OCR，请设置</font></font><code>OCR_ENGINE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>None</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转换单个文件</font></font></h2><a id="user-content-convert-a-single-file" class="anchor" aria-label="永久链接：转换单个文件" href="#convert-a-single-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>marker_single /path/to/file.pdf /path/to/output/folder --batch_multiplier 2 --max_pages 10 --langs English</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="marker_single /path/to/file.pdf /path/to/output/folder --batch_multiplier 2 --max_pages 10 --langs English" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><code>--batch_multiplier</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是如果您有额外的 VRAM，默认批处理大小要乘以的数值。数字越大，占用的 VRAM 越多，但处理速度越快。默认设置为 2。默认批处理大小将占用约 3GB 的 VRAM。</font></font></li>
<li><code>--max_pages</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是要处理的最大页数。忽略此项可转换整个文档。</font></font></li>
<li><code>--langs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是文档中用于 OCR 的语言的逗号分隔列表</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保</font></font><code>DEFAULT_LANG</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置适合您的文档。OCR 支持的语言列表在</font></font><a href="https://github.com/VikParuchuri/surya/blob/master/surya/languages.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里。如果您需要更多语言，您可以使用</font></font></a><font style="vertical-align: inherit;"></font><a href="https://tesseract-ocr.github.io/tessdoc/Data-Files#data-files-for-version-400-november-29-2016" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tesseract</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的任何语言（</font><font style="vertical-align: inherit;">如果您设置</font></font><code>OCR_ENGINE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为）</font></font><code>ocrmypdf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。如果您不需要 OCR，标记可以使用任何语言。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转换多个文件</font></font></h2><a id="user-content-convert-multiple-files" class="anchor" aria-label="永久链接：转换多&ZeroWidthSpace;&ZeroWidthSpace;个文件" href="#convert-multiple-files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>marker /path/to/input/folder /path/to/output/folder --workers 10 --max 10 --metadata_file /path/to/metadata.json --min_length 10000</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="marker /path/to/input/folder /path/to/output/folder --workers 10 --max 10 --metadata_file /path/to/metadata.json --min_length 10000" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><code>--workers</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一次要转换的 PDF 数量。默认情况下，此值设置为 1，但您可以增加此值以增加吞吐量，但代价是增加 CPU/GPU 使用率。</font></font><code>INFERENCE_RAM / VRAM_PER_TASK</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 GPU，则并行度不会增加。</font></font></li>
<li><code>--max</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是要转换的 PDF 的最大数量。省略此项可转换文件夹中的所有 PDF。</font></font></li>
<li><code>--min_length</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是需要从 PDF 中提取的最少字符数，然后才会考虑进行处理。如果您要处理大量 PDF，我建议设置此项以避免对大部分是图像的 PDF 进行 OCR。（这会减慢一切速度）</font></font></li>
<li><code>--metadata_file</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是包含有关 pdf 元数据的 json 文件的可选路径。如果您提供它，它将用于设置每个 pdf 的语言。如果没有，</font></font><code>DEFAULT_LANG</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将使用。格式为：</font></font></li>
</ul>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>{
  "pdf1.pdf": {"languages": ["English"]},
  "pdf2.pdf": {"languages": ["Spanish", "Russian"]},
  ...
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
  &quot;pdf1.pdf&quot;: {&quot;languages&quot;: [&quot;English&quot;]},
  &quot;pdf2.pdf&quot;: {&quot;languages&quot;: [&quot;Spanish&quot;, &quot;Russian&quot;]},
  ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用语言名称或代码。具体代码取决于 OCR 引擎。请参阅</font></font><a href="https://github.com/VikParuchuri/surya/blob/master/surya/languages.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看 surya 代码的完整列表，并参阅</font></font><a href="https://tesseract-ocr.github.io/tessdoc/Data-Files#data-files-for-version-400-november-29-2016" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看 tesseract 代码的完整列表。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在多个 GPU 上转换多个文件</font></font></h2><a id="user-content-convert-multiple-files-on-multiple-gpus" class="anchor" aria-label="永久链接：在多个 GPU 上转换多个文件" href="#convert-multiple-files-on-multiple-gpus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>MIN_LENGTH=10000 METADATA_FILE=../pdf_meta.json NUM_DEVICES=4 NUM_WORKERS=15 marker_chunk_convert ../pdf_in ../md_out</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="MIN_LENGTH=10000 METADATA_FILE=../pdf_meta.json NUM_DEVICES=4 NUM_WORKERS=15 marker_chunk_convert ../pdf_in ../md_out" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><code>METADATA_FILE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是包含 pdf 元数据的 json 文件的可选路径。请参阅上文了解格式。</font></font></li>
<li><code>NUM_DEVICES</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是要使用的 GPU 数量。应大于</font></font><code>2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或等于。</font></font></li>
<li><code>NUM_WORKERS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是每个 GPU 上运行的并行进程数。每个 GPU 的并行度不会超过</font></font><code>INFERENCE_RAM / VRAM_PER_TASK</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><code>MIN_LENGTH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是需要从 PDF 中提取的最少字符数，然后才会考虑进行处理。如果您要处理大量 PDF，我建议设置此项以避免对大部分是图像的 PDF 进行 OCR。（这会减慢一切速度）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，上述环境变量特定于此脚本，并且无法在中设置</font></font><code>local.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">故障排除</font></font></h1><a id="user-content-troubleshooting" class="anchor" aria-label="永久链接：故障排除" href="#troubleshooting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果事情没有按照你预期的方式进行，你可能会发现一些设置很有用：</font></font></p>
<ul dir="auto">
<li><code>OCR_ALL_PAGES</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 将其设置为 true 以强制对所有页面进行 OCR。如果默认情况下无法正确识别表格布局，或者文本混乱，则此功能非常有用。</font></font></li>
<li><code>TORCH_DEVICE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 将其设置为强制标记使用给定的火炬设备进行推理。</font></font></li>
<li><code>OCR_ENGINE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 可以将其设置为</font></font><code>surya</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>ocrmypdf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><code>DEBUG</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 将此设置为</font></font><code>True</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在转换多个 pdf 时显示射线日志</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请验证您是否正确设置了语言，或者传递了元数据文件。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果出现内存不足错误，请减少工作器数量（增加设置</font></font><code>VRAM_PER_TASK</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。您还可以尝试将较长的 PDF 拆分为多个文件。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般来说，如果输出结果不符合您的预期，尝试对 PDF 进行 OCR 是一个不错的第一步。并非所有 PDF 都嵌入了良好的文本/框。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准</font></font></h1><a id="user-content-benchmarks" class="anchor" aria-label="固定链接：基准测试" href="#benchmarks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对 PDF 提取质量进行基准测试很难。我通过查找具有 pdf 版本和 latex 源的书籍和科学论文创建了一个测试集。我将 latex 转换为文本，并将参考与文本提取方法的输出进行比较。它很嘈杂，但至少在方向上是正确的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准测试表明 marker 比 nougat 快 4 倍，而且在 arXiv 之外更准确（nougat 是在 arXiv 数据上训练的）。我们展示了简单的文本提取（从 pdf 中提取文本而不进行任何处理）以进行比较。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">速度</font></font></strong></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方法</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平均分</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每页时间</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每份文件的时间</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.613721</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.631991</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">58.1432</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">牛轧糖</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.406603</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.59702</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">238.926</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">准确性</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前 3 本是非 arXiv 书籍，后 3 本是 arXiv 论文。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方法</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多列卷积神经网络.pdf</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开关转换.pdf</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">thinkpython.pdf</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">思考.pdf</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">思考DSP.pdf</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人群.pdf</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.536176</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.516833</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.70515</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.710657</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.690042</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.523467</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">牛轧糖</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.44009</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.588973</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.322706</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.401342</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.160842</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.525663</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准测试期间的 GPU 内存使用峰值</font></font><code>4.2GB</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于 nougat 和</font></font><code>4.1GB</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">marker。基准测试在 A6000 Ada 上运行。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">吞吐量</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标记每个任务平均占用大约 4GB 的 VRAM，因此您可以在 A6000 上并行转换 12 个文档。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/VikParuchuri/marker/blob/master/data/images/per_doc.png"><img src="/VikParuchuri/marker/raw/master/data/images/per_doc.png" alt="基准测试结果" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行自己的基准测试</font></font></h2><a id="user-content-running-your-own-benchmarks" class="anchor" aria-label="永久链接：运行你自己的基准测试" href="#running-your-own-benchmarks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在您的机器上对 marker 的性能进行基准测试。使用以下命令手动安装 marker：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/VikParuchuri/marker.git
poetry install</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/VikParuchuri/marker.git
poetry install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://drive.google.com/file/d/1ZSeWDo2g1y0BRLT7KnbmytV2bjWARWba/view?usp=sharing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载基准测试数据</font><font style="vertical-align: inherit;">并解压。然后</font></font><code>benchmark.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">像这样运行：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python benchmark.py data/pdfs data/references report.json --nougat</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python benchmark.py data/pdfs data/references report.json --nougat" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将对 marker 与其他文本提取方法进行基准测试。它为 nougat 和 marker 设置批处理大小，以便每个方法使用类似数量的 GPU RAM。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">忽略</font></font><code>--nougat</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以将 Nougat 从基准测试中排除。我不建议在 CPU 上运行 Nougat，因为它非常慢。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谢谢</font></font></h1><a id="user-content-thanks" class="anchor" aria-label="永久链接：谢谢" href="#thanks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果没有出色的开源模型和数据集，这项工作就不可能实现，其中（包括但不限于）：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">苏里亚</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特克西菲</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pypdfium2/pdfium</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IBM 的 DocLayNet</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自 Google 的 ByT5</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢这些模型和数据集的作者将它们提供给社区！</font></font></p>
</article></div>
