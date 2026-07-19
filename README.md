<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Obsidian Didone Font Family</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 850px;
            margin: 0 auto;
            padding: 40px 20px;
            background-color: #ffffff;
        }
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        .badge {
            display: inline-block;
            height: 28px;
            margin: 0 4px;
        }
        h1 {
            font-size: 2.5em;
            margin: 20px 0 10px 0;
            font-family: "Times New Roman", Times, serif;
            background: linear-gradient(to right, #2c3e50, #7f8c8d);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .subtitle {
            font-size: 1.15em;
            color: #586069;
            max-width: 600px;
            margin: 10px auto;
        }
        .author-notice {
            color: #6a737d;
            font-size: 0.95em;
        }
        hr {
            border: 0;
            height: 1px;
            background: linear-gradient(to right, rgba(0,0,0,0), rgba(0,0,0,0.1), rgba(0,0,0,0));
            margin: 40px 0;
        }
        h3 {
            font-size: 1.35em;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 30px;
            color: #24292e;
        }
        .feature-table {
            width: 100%;
            border-collapse: separate;
            border-spacing: 15px 0;
            margin: 20px -15px;
        }
        .feature-card {
            border: 1px solid #e1e4e8;
            border-radius: 6px;
            padding: 20px;
            vertical-align: top;
            background-color: #fff;
            box-shadow: 0 1px 3px rgba(0,0,0,0.02);
        }
        .feature-card h4 {
            margin-top: 0;
            font-size: 1.1em;
            color: #0366d6;
        }
        .feature-card p {
            font-size: 0.9em;
            color: #586069;
            margin-bottom: 0;
        }
        .list-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        .list-table th, .list-table td {
            border: 1px solid #dfe2e5;
            padding: 12px 15px;
            text-align: left;
        }
        .list-table th {
            background-color: #f6f8fa;
            font-weight: 600;
        }
        .list-table tr:nth-child(even) {
            background-color: #f8f9fa;
        }
        .preview-container {
            text-align: center;
            background-color: #f6f8fa;
            padding: 30px;
            border-radius: 8px;
            border: 1px solid #e1e4e8;
            margin: 20px 0;
        }
        .preview-image {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        .preview-tip {
            color: #6a737d;
            font-size: 0.85em;
            margin-top: 15px;
            margin-bottom: 0;
        }
        blockquote {
            margin: 20px 0;
            padding: 0 1em;
            color: #6a737d;
            border-left: 0.25em solid #dfe2e5;
            background-color: #fafbfc;
            padding: 10px 15px;
        }
        .rules-list {
            padding-left: 20px;
            font-size: 0.95em;
        }
        .rules-list li {
            margin-bottom: 8px;
        }
        .footer {
            text-align: center;
            color: #999;
            font-size: 0.85em;
            margin-top: 60px;
        }
        .footer a {
            color: #0366d6;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="header">
    <!-- 顶部的动态徽章图片 -->
    <img class="badge" src="https://shields.io" alt="License">
    <img class="badge" src="https://shields.io" alt="Language">
    <img class="badge" src="https://shields.io" alt="AI-Tool">

    <h1>🖋️ Obsidian Didone</h1>
    <p class="subtitle">一个将现代 AI 设计美学与经典开源宋体完美融合的多语言衬线字体家族（Serif Font Family）。</p>
    <p class="author-notice">西文部分由 <b>Mixfont AI</b> 倾力打造，中日韩部分由 <b>思源宋体 (Source Han Serif)</b> 完美补全。</p>
</div>

<hr>

<h3>💎 核心设计特性</h3>
<table class="feature-table">
    <tr>
        <td class="feature-card" width="50%">
            <h4>🌌 西文：高冷 Didone 风格</h4>
            <p>极致的粗细线条对比，垂直分明的字轴。传承自经典 Didot 刻本的优雅风骨，由 AI 进行现代化的视觉修正，极具视觉冲击力。</p>
        </td>
        <td class="feature-card" width="50%">
            <h4>🌏 中日韩：思源补全</h4>
            <p>采用 Adobe 与 Google 联合开发的思源宋体作为底噪，提供多达数万字的完美 CJK 字形支持，彻底告别中文排版乱码与缺字烦恼。</p>
        </td>
    </tr>
</table>

<h3>📦 字体家族清单 (Font Family)</h3>
<table class="list-table">
    <thead>
        <tr>
            <th>📄 字体文件名</th>
            <th>🌐 覆盖语种与版本说明</th>
            <th>💾 文件体积</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>Obsidian-Didone-Regular.ttf</code></td>
            <td><b>原生西文</b> (AI 纯享版，不含中文字符)</td>
            <td><code>~38 KB</code></td>
        </tr>
        <tr>
            <td><code>ObsidianDidoneSC-Regular.ttf</code></td>
            <td><b>简体中文</b> (Simplified Chinese 补全)</td>
            <td><code>~14.4 MB</code></td>
        </tr>
        <tr>
            <td><code>ObsidianDidoneTC-Regular.ttf</code></td>
            <td><b>繁体中文</b> (Traditional Chinese 台湾标准)</td>
            <td><code>~15.5 MB</code></td>
        </tr>
        <tr>
            <td><code>ObsidianDidoneHK-Regular.ttf</code></td>
            <td><b>繁体中文</b> (Traditional Chinese 香港标准)</td>
            <td><code>~15.5 MB</code></td>
        </tr>
        <tr>
            <td><code>ObsidianDidoneJP-Regular.ttf</code></td>
            <td><b>日文字体</b> (Japanese 补全)</td>
            <td><code>~14.6 MB</code></td>
        </tr>
        <tr>
            <td><code>ObsidianDidoneKR-Regular.ttf</code></td>
            <td><b>韩文字体</b> (Korean 补全)</td>
            <td><code>~22.7 MB</code></td>
        </tr>
    </tbody>
</table>

<h3>🎨 字体效果预览 (Preview)</h3>
<div class="preview-container">
    <!-- 如果你有预览图，重命名为 preview.png 放在同目录下，就会自动显示 -->
    <img class="preview-image" src="preview.png" alt="Obsidian Didone Preview Placeholder">
    <p class="preview-tip">💡 提示：将你的字体样张截图命名为 preview.png 并存放在网页同目录下即可替换此区域</p>
</div>

<h3>📜 授权与使用守则 (License)</h3>
<blockquote>
    <p><b>100% 允许免费商业使用！</b> 本衍生字体受 <b>SIL Open Font License 1.1</b> 开源协议保护。</p>
</blockquote>
<ul class="rules-list">
    <li><b>🟢 允许做的事</b>：在任何商业/非商业设计、印刷、网站内嵌、游戏、APP、视频内使用。在保持本协议的前提下，允许对其进行二次修改、重命名并再次发布。</li>
    <li><b>🔴 禁止做的事</b>：<b>严禁</b> 将此字体文件单独挂在网上进行售卖。如果在发布衍生版本时闭源，或移除原本的版权声明，将视作侵权。</li>
</ul>

<div class="footer">
    <p>Detailed contributor metadata can be verified in the <a href="AUTHORS.txt">AUTHORS</a> file.</p>
    <p>Created with ❤️ by HinataHikari69</p>
</div>

</body>
</html>
