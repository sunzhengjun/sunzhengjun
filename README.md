<!-- 顶部 SVG Banner -->
<p align="center">
  <img src="https://raw.githubusercontent.com/sunzhengjun/sunzhengjun/main/pipeline-banner.svg" alt="Automation Pipeline Banner" />
</p>

<!-- Badge 行 -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sunzhengjun&label=Visitors&color=0e75b6&style=for-the-badge" alt="访客统计" />
  <img src="https://img.shields.io/badge/Followers-1.2k-0d6efd?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/github/stars/sunzhengjun?style=for-the-badge&logo=github&label=Stars&color=facc15" alt="GitHub Stars" />
</p>

---

<!-- About Me · Elegant SVG Card -->
<svg viewBox="0 0 1200 360" width="100%" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="title desc">
  <title id="title">About Me</title>
  <desc id="desc">A short introduction card rendered with pure SVG</desc>

  <defs>
    <!-- 背景投影 -->
    <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur in="SourceAlpha" stdDeviation="12" result="blur"/>
      <feOffset dy="8" result="offset"/>
      <feColorMatrix in="offset" type="matrix"
        values="0 0 0 0 0
                0 0 0 0 0
                0 0 0 0 0
                0 0 0 0.20 0" result="shadow"/>
      <feBlend in="SourceGraphic" in2="shadow" mode="normal"/>
    </filter>

    <!-- 渐变描边 -->
    <linearGradient id="gradStroke" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%"  stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#22C55E"/>
    </linearGradient>

    <!-- 标题文字渐变 -->
    <linearGradient id="gradTitle" x1="0" x2="1" y1="0" y2="0">
      <stop offset="0%"  stop-color="#60A5FA"/>
      <stop offset="50%" stop-color="#A78BFA"/>
      <stop offset="100%" stop-color="#34D399"/>
    </linearGradient>

    <!-- 分隔线发光 -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- 主题适配（GitHub 支持） -->
    <style>
      :root { --fg:#0f172a; --muted:#475569; --panel:#ffffff; }
      @media (prefers-color-scheme: dark) {
        :root { --fg:#e5e7eb; --muted:#94a3b8; --panel:#0b1220; }
      }
      .fg{ fill: var(--fg); }
      .muted{ fill: var(--muted); }
      .panel{ fill: var(--panel); }
    </style>
  </defs>

  <!-- 卡片 -->
  <rect x="40" y="32" width="1120" height="296" rx="24"
        class="panel" filter="url(#softShadow)" />
  <rect x="40.5" y="32.5" width="1119" height="295" rx="24"
        fill="none" stroke="url(#gradStroke)" stroke-width="1.5"/>

  <!-- 标题 -->
  <g text-anchor="middle" transform="translate(600,100)">
    <text font-size="28" font-family="Segoe UI, Inter, system-ui, -apple-system, Noto Sans CJK SC, Microsoft YaHei"
          font-weight="700" fill="url(#gradTitle)">
      👨‍💻 简介 · About Me
    </text>

    <!-- 分隔线 -->
    <g transform="translate(0,20)" filter="url(#glow)">
      <rect x="-120" y="10" width="240" height="2.5" fill="url(#gradStroke)" rx="2"/>
    </g>
  </g>

  <!-- 正文 -->
  <g transform="translate(140,160)">
    <text class="fg" font-size="20" xml:space="preserve"
          font-family="Segoe UI, Inter, system-ui, -apple-system, Noto Sans CJK SC, Microsoft YaHei">
      <tspan x="0" dy="0">Unity 世界的七年老玩家。</tspan>
      <tspan x="0" dy="34" class="muted">技能树点满：从零造物、工具链自动化、以及「在线热修复」的魔法。</tspan>
      <tspan x="0" dy="34" class="muted">日常工作是说服各个平台乖乖自动构建，终极目标——让版本发布像发条消息一样轻松。</tspan>
      <tspan x="0" dy="34" class="muted">一个对优雅代码与高效工具始终保持热忱的「技术手艺人」。</tspan>
    </text>
  </g>

  <!-- 右下角徽记 -->
  <g transform="translate(1040,280)">
    <circle r="8" fill="url(#gradStroke)"/>
    <text x="14" y="5" class="muted" font-size="12"
          font-family="Segoe UI, Inter, system-ui, -apple-system">crafted in SVG</text>
  </g>
</svg>


<h2 align="center">👨‍💻 简介 · About Me</h2>

<p align="center">
  Unity 世界的七年老玩家。<br/>
  技能树点满：从零造物、工具链自动化、以及「在线热修复」的魔法。<br/>
  日常工作是说服各个平台乖乖自动构建，终极目标——让版本发布像发条消息一样轻松。<br/>
  一个对优雅代码与高效工具始终保持热忱的「技术手艺人」。
</p>

<hr/>

## 🛠 技能图谱 · Tech Stack

**Languages & Engine**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![BAT](https://img.shields.io/badge/Batch%20Script-4D4D4D?style=flat-square&logo=windows-terminal&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

**Tools & IDE**

![Rider](https://img.shields.io/badge/Rider-000000?style=flat-square&logo=Rider&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Fork](https://img.shields.io/badge/Fork-2D333B?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Mockoon](https://img.shields.io/badge/Mockoon-4E8CEE?style=flat-square&logo=mockoon&logoColor=white)
![AutoHotkey](https://img.shields.io/badge/AutoHotKey-334455?style=flat-square&logo=autohotkey&logoColor=white)
![Odin Inspector](https://img.shields.io/badge/Odin%20Inspector-512BD4?style=flat-square)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Spine](https://img.shields.io/badge/Spine-FF0000?style=flat-square&logo=spine&logoColor=white)

**Game Dev & Workflow**

![Game Frameworks](https://img.shields.io/badge/Game%20Frameworks-8A2BE2?style=flat-square)
![HybridCLR](https://img.shields.io/badge/HybridCLR-FF8C00?style=flat-square)
![Unity Editor Tools](https://img.shields.io/badge/Unity%20Editor%20Tools-4CAF50?style=flat-square)
![Build & CI/CD](https://img.shields.io/badge/Build%20%26%20CI%2FCD-2196F3?style=flat-square)
![ECS](https://img.shields.io/badge/ECS-0078D7?style=flat-square)
![UGUI](https://img.shields.io/badge/UGUI-00BFA6?style=flat-square)
![NGUI](https://img.shields.io/badge/NGUI-FF6F00?style=flat-square)
![FGUI](https://img.shields.io/badge/FGUI-9C27B0?style=flat-square)

---


## 💡 技术魔法 Highlights

- **🚀 构建流水线革命**：重塑 Android/iOS 构建管线，将构建时间从“一杯咖啡”压缩至“一口咖啡”，整体效率提升约 **60%**。  
- **🔄 资源协作战役**：打造资源与配置自动化同步体系，让美术与策划告别命名纠纷与手动拖拽，协作效率提升约 **30%**。  
- **🎨 美术资源配置化**：为美术资源开发标准化 GUI 工具链，实现关键资源配置“一键生成”，将重复劳动转化为创意时间，效率提升约 **50%**。  
- **⚡ 热更新架构进化**：深度重构 HybridCLR 热更新体系，不仅让加载体验“无缝丝滑”，更使带宽成本骤降约 **42%**。  
- **🧰 自研编辑器武器库**：打造涵盖技能编辑、资源筛查、一键生成等功能的 Editor 插件集，将 Unity Editor 打造成团队专属神兵。  

---


## 🌌 项目光谱 Project Spectrum

- **「构建次元」折叠术**：将 Android / iOS 的构建、上传等多维流程折叠为“一念即成”的单点事件，让时间在编译的缝隙中加速流逝。  
- **「资源通语」编织者**：为策划与美术打造一种名为 “Excel” 的通用语，使其所念即所得，命名与资源在虚实之间自动同步，消弭协作的巴别塔。  
- **「热更幻境」漫游指南**：在 HybridCLR 之上重构代码与资源的在线幻境，赋予其“瞬移”的加载与“时光倒流”的回滚，让用户徜徉于无缝的体验之流。  

---


## 📊 GitHub 统计
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sunzhengjun&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=sunzhengjun&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## 📚 技术分享 & 开源贡献

- 🔗 [HybridCLR 热更新实战指南](https://github.com/sunzhengjun/HybridCLRGuide)
- 🧩 [Unity Editor 扩展最佳实践](https://github.com/sunzhengjun/UnityEditorTools)
- 🧰 [GameFramework 模块化设计](https://github.com/sunzhengjun/GameFrameworkDemo)

---

## 📫 联系方式 · Contact Me

<p align="center">
  💬 <a href="1139210500@qq.com">Email</a> • 
  🌐 <a href="https://github.com/sunzhengjun">GitHub</a> • 
</p>

<p align="center">
  <em>“让复杂的开发流程自动化，让游戏开发更纯粹。”</em>
</p>

---

<!-- 底部签名 -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d6efd&height=100&section=footer"/>
</p>

