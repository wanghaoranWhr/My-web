<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<h1>📦 基于时序预测模型的农田害虫预警系统</h1>
<p>本项目为华中科技大学大学生创新创业训练项目，面向粮食安全与绿色植保需求，针对农田害虫“突发性高、时序高度偏态、爆发样本稀缺、预测易误报”痛点，构建基于CNN-LSTM的多任务时序预警模型，实现褐飞虱、稻瘿蚊、青叶蝉、稻纵卷叶螟、白背飞虱多品种害虫智能预警。</p>
<div>
    <span class="badge">版本 v1.0.0</span>
    <span class="badge">开源协议 MIT</span>
    <span class="badge">语言 HTML/CSS/JS</span>
</div>
<div class="section">
    <h2>✨ 项目特色</h2>
    <ul>
        <li>特色 1：双任务协同预测，分类头判定爆发时间，回归头预测爆发强度，模型精度与稳定性显著优于传统单任务模型</li>
        <li>特色 2：生物驱动特征工程，构建4周滚动累积气象特征，精准捕捉环境累积效应对虫害发生的滞后驱动作用，符合生物学规律</li>
        <li>特色 3：梯度加权联合损失，Focal Loss聚焦爆发拐点，Huber Loss增强极值鲁棒性，加权强化分类信号，有效降低漏报率</li>
        <li>特色 4：创新硬门控决策机制，先判概率、后定强度，强制截断非爆发期异常预测值，从根源消除伪爆发误报</li>
        <li>特色 5：数据高度统一规范，采用同一区域、单一虫种、光诱捕法采集数据，数据集标准统一、时序连续，可解释性强</li>
        <li>特色 6：贯彻植保优先原则，以“不漏报”为第一目标，高度贴合田间实际防控需求</li>
        <li>特色 7：模型轻量高效易部署，结构简洁、推理快速，成本低、无需高端设备，易于田间推广落地</li>
        <li>特色 8：框架具备强可迁移性，可直接迁移至褐飞虱、白背飞虱、三化螟、叶蝉等同类害虫预警场景</li>
    </ul>

</div>

<div class="section">
    <h2>🚀 准备</h2>
    <h3>1. 配置要求</h3>
    首先，确保你的计算机上已经安装python和pytorch，也可应用Google提供的colab完成代码实现。
    <h3>2. 进入目录</h3>
    <pre><code>cd 项目名</code></pre>

    <h3>3. 运行 / 使用</h3>
    <pre><code># 直接打开 index.html 即可使用
# 启动</code></pre>
</div>

<div class="section">
    <h2>📁 项目结构</h2>
    <pre><code>├── index.html       # 主入口文件
├── css/             # 样式文件
├── js/              # 脚本文件
├── assets/          # 图片、字体等资源
└── README.html      # 项目说明文档</code></pre>
</div>

<div class="section">
    <h2>📌 使用示例</h2>
    <p>展示核心功能代码或效果：</p>
    <pre><code>&lt;div class="demo"&gt;
  这里是使用示例代码
&lt;/div&gt;</code></pre>
</div>

<div class="section">
    <h2>🤝 贡献指南</h2>
    <ol>
        <li>Fork 本项目</li>
        <li>创建功能分支：<code>git checkout -b feature/xxx</code></li>
        <li>提交修改：<code>git commit -m 'Add some feature'</code></li>
        <li>推送到分支：<code>git push origin feature/xxx</code></li>
        <li>提交 Pull Request</li>
    </ol>
</div>

<div class="section">
    <h2>📄 开源协议</h2>
    <p>本项目基于 <a href="https://opensource.org/licenses/MIT" target="_blank">MIT 协议</a> 开源，可自由使用、修改、分发。</p>
</div>

<div class="section">
    <h2>📞 联系与反馈</h2>
    <p>如有问题或建议，欢迎提交 <a href="#">Issue</a> 或邮件联系：<code>your-email@example.com</code></p>
</div>

<div class="footer">
    © 2026 你的用户名 | Made with ❤️ on GitHub
</div>

</body>
</html>
