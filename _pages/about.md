---
layout: about
title: about
permalink: /
subtitle: >
  B.Sc. Computational Finance (Talented Program) · <a href="https://www.cb.cityu.edu.hk/" target="_blank">City University of Hong Kong</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Hong Kong SAR, China</p>
    <p>📧 <a href="mailto:jiaooozun@gmail.com">jiaooozun@gmail.com</a></p>
    <p>📧 <a href="mailto:xintonmou2-c@my.cityu.edu.hk">xintonmou2-c@my.cityu.edu.hk</a></p>

selected_papers: false
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a third-year undergraduate in the **Computational Finance Talented Program** at City University of Hong Kong's College of Business (sGPA: 4.05/4.30, Full Tuition Scholarship). My research interests lie at the intersection of **corporate governance & ESG**, **causal inference**, and **quantitative finance**.

I am currently the lead researcher on an independent study supervised by [Prof. LUO Rui](https://www.cb.cityu.edu.hk/) at CityU, examining the causal effects of board composition on ESG disclosure across a panel of over one million corporate records. The project applies the [Callaway & Sant'Anna (2021)](https://doi.org/10.1016/j.jeconom.2020.12.001) difference-in-differences estimator, Social Network Analysis, and Oster's (2019) sensitivity tests to address endogeneity in staggered adoption designs.

In quantitative trading, I placed **23rd out of 2,695 teams (Top 0.85% globally)** as Team Captain in the 2025 Bloomberg Global Trading Competition, managing a $1M simulated portfolio to a $102K realized P&L over five weeks. I have also passed the **CFA Level I** examination.

On the industry side, I interned at **Sinolink Securities** (New Energy / Hydrogen Group) and **Huatai Securities**, where I built quantitative trading strategies, conducted carbon market research, and contributed to a live multi-asset strategy now integrated into the Huatai Zhangle Wealth app. I previously co-founded **DecentraScholars**, a DeSci startup incubated by [HK Tech 300](https://www.hktech300.hk/) and HKSTP, architecting a Multi-Agent System for automated research workflows on a Solana/Arweave data layer.

I am broadly interested in opportunities at the intersection of academic research and applied finance — feel free to reach out.

<!-- Guppy floating fish widget -->
<div id="guppy-widget">
  <button id="guppy-btn" onclick="toggleGuppy()" title="Chat with Guppy 🐠" aria-label="Chat with Guppy">
    🐠
  </button>
  <div id="guppy-chat" role="dialog" aria-label="Guppy chat">
    <div id="guppy-header">
      <span>🐠 &nbsp;Chat with Guppy</span>
      <button onclick="toggleGuppy()" aria-label="Close">✕</button>
    </div>
    <iframe src="https://arman-bd.github.io/guppylm/"
            id="guppy-iframe"
            title="Guppy chat"
            loading="lazy"
            frameborder="0">
    </iframe>
  </div>
</div>

<style>
#guppy-widget {
  position: fixed;
  bottom: 28px;
  right: 28px;
  z-index: 9999;
}
#guppy-btn {
  width: 54px;
  height: 54px;
  border-radius: 50%;
  border: none;
  background: #3d8ef0;
  font-size: 26px;
  cursor: pointer;
  box-shadow: 0 4px 14px rgba(0,0,0,0.22);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
  display: flex;
  align-items: center;
  justify-content: center;
  line-height: 1;
}
#guppy-btn:hover {
  transform: scale(1.12);
  box-shadow: 0 6px 20px rgba(0,0,0,0.3);
}
#guppy-chat {
  display: none;
  position: fixed;
  bottom: 96px;
  right: 28px;
  width: 370px;
  height: 510px;
  border-radius: 16px;
  overflow: hidden;
  box-shadow: 0 8px 36px rgba(0,0,0,0.22);
  flex-direction: column;
  animation: guppyPop 0.2s ease;
}
#guppy-chat.open { display: flex; }
@keyframes guppyPop {
  from { opacity: 0; transform: translateY(12px) scale(0.97); }
  to   { opacity: 1; transform: translateY(0)   scale(1);    }
}
#guppy-header {
  background: #3d8ef0;
  color: #fff;
  padding: 10px 16px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 13px;
  font-weight: 600;
  flex-shrink: 0;
}
#guppy-header button {
  background: none;
  border: none;
  color: #fff;
  font-size: 17px;
  cursor: pointer;
  padding: 0;
  line-height: 1;
  opacity: 0.85;
}
#guppy-header button:hover { opacity: 1; }
#guppy-iframe {
  flex: 1;
  width: 100%;
  border: none;
}
</style>

<script>
function toggleGuppy() {
  document.getElementById('guppy-chat').classList.toggle('open');
}
</script>
