<div align="center">

<!-- HERO SECTION - Dramatic Entry -->
<div style="background: linear-gradient(135deg, #0F2E1E 0%, #1A4A2E 50%, #0D1F16 100%); padding: 80px 20px; position: relative; overflow: hidden; border-radius: 20px; margin: 20px 0;">

<!-- Animated Background Elements -->
<style>
  @keyframes float {
    0%, 100% { transform: translateY(0px) translateX(0px); opacity: 0.3; }
    50% { transform: translateY(-30px) translateX(15px); opacity: 0.1; }
  }
  
  @keyframes glow-pulse {
    0%, 100% { box-shadow: 0 0 20px rgba(173, 235, 179, 0.3); }
    50% { box-shadow: 0 0 40px rgba(173, 235, 179, 0.6); }
  }
  
  @keyframes gradient-shift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  @keyframes slide-in-up {
    from { 
      opacity: 0; 
      transform: translateY(30px); 
    }
    to { 
      opacity: 1; 
      transform: translateY(0); 
    }
  }
  
  .hero-blob {
    position: absolute;
    border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%;
    animation: float 8s ease-in-out infinite;
    background: radial-gradient(circle at 30% 30%, rgba(173, 235, 179, 0.15), rgba(173, 235, 179, 0));
  }
  
  .hero-title {
    font-size: 48px;
    font-weight: 900;
    letter-spacing: -2px;
    background: linear-gradient(135deg, #ADEBB3 0%, #7FD18E 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin: 0;
    animation: slide-in-up 0.8s ease-out;
    position: relative;
    z-index: 10;
  }
  
  .hero-subtitle {
    font-size: 20px;
    color: #ADEBB3;
    margin-top: 12px;
    animation: slide-in-up 0.8s ease-out 0.2s both;
    font-weight: 500;
    letter-spacing: 1px;
    position: relative;
    z-index: 10;
  }
  
  .hero-description {
    font-size: 16px;
    color: #8DB896;
    max-width: 600px;
    margin: 20px auto;
    line-height: 1.6;
    animation: slide-in-up 0.8s ease-out 0.4s both;
    position: relative;
    z-index: 10;
  }
</style>

<div class="hero-blob" style="width: 300px; height: 300px; top: -100px; right: -50px;"></div>
<div class="hero-blob" style="width: 200px; height: 200px; bottom: -80px; left: 10%; animation-delay: 2s;"></div>

<h1 class="hero-title">Nitish Kumar</h1>
<p class="hero-subtitle">DATA SCIENTIST • ML ENGINEER • PROBLEM SOLVER</p>
<p class="hero-description">Transforming raw data into intelligent solutions. Crafting machine learning models that make a real impact. Based in Bangalore, building the future of AI 🚀</p>

</div>

---

<!-- STATS SECTION -->
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 40px 0; padding: 0 20px;">

<div style="background: rgba(173, 235, 179, 0.1); border: 1px solid rgba(173, 235, 179, 0.3); padding: 25px; border-radius: 16px; backdrop-filter: blur(10px); transition: all 0.3s ease;">
  <div style="font-size: 32px; font-weight: 900; color: #ADEBB3;">80+</div>
  <div style="color: #8DB896; font-size: 14px; margin-top: 8px; text-transform: uppercase; letter-spacing: 1px;">Projects Built</div>
</div>

<div style="background: rgba(173, 235, 179, 0.1); border: 1px solid rgba(173, 235, 179, 0.3); padding: 25px; border-radius: 16px; backdrop-filter: blur(10px); transition: all 0.3s ease;">
  <div style="font-size: 32px; font-weight: 900; color: #ADEBB3;">500K+</div>
  <div style="color: #8DB896; font-size: 14px; margin-top: 8px; text-transform: uppercase; letter-spacing: 1px;">Data Points Processed</div>
</div>

<div style="background: rgba(173, 235, 179, 0.1); border: 1px solid rgba(173, 235, 179, 0.3); padding: 25px; border-radius: 16px; backdrop-filter: blur(10px); transition: all 0.3s ease;">
  <div style="font-size: 32px; font-weight: 900; color: #ADEBB3;">15+</div>
  <div style="color: #8DB896; font-size: 14px; margin-top: 8px; text-transform: uppercase; letter-spacing: 1px;">ML Models Deployed</div>
</div>

<div style="background: rgba(173, 235, 179, 0.1); border: 1px solid rgba(173, 235, 179, 0.3); padding: 25px; border-radius: 16px; backdrop-filter: blur(10px); transition: all 0.3s ease;">
  <div style="font-size: 32px; font-weight: 900; color: #ADEBB3;">2026</div>
  <div style="color: #8DB896; font-size: 14px; margin-top: 8px; text-transform: uppercase; letter-spacing: 1px;">Year of Impact</div>
</div>

</div>

---

<!-- FEATURED WORK SECTION -->

## ⚡ Highlighted Projects

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin: 40px 0; padding: 0 20px;">

<!-- Project Card 1 -->
<div style="background: linear-gradient(135deg, rgba(26, 74, 46, 0.8) 0%, rgba(13, 31, 22, 0.9) 100%); border: 1px solid rgba(173, 235, 179, 0.2); padding: 30px; border-radius: 16px; backdrop-filter: blur(20px); transition: all 0.4s cubic-bezier(0.23, 1, 0.320, 1); cursor: pointer; position: relative; overflow: hidden;">

<style>
  @keyframes card-glow {
    0%, 100% { border-color: rgba(173, 235, 179, 0.2); }
    50% { border-color: rgba(173, 235, 179, 0.5); }
  }
  
  @keyframes icon-bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }
</style>

<div style="font-size: 40px; margin-bottom: 15px; animation: icon-bounce 3s ease-in-out infinite;">🤖</div>
<h3 style="color: #ADEBB3; font-size: 22px; margin: 0 0 12px 0; font-weight: 700;">Fake News Detector</h3>
<p style="color: #8DB896; font-size: 14px; line-height: 1.6; margin: 0;">NLP-powered misinformation classifier achieving 94% accuracy. Built with transformers and deployed on production servers.</p>
<div style="display: flex; gap: 8px; margin-top: 15px; flex-wrap: wrap;">
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">NLP</span>
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">Transformers</span>
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">Python</span>
</div>
</div>

<!-- Project Card 2 -->
<div style="background: linear-gradient(135deg, rgba(26, 74, 46, 0.8) 0%, rgba(13, 31, 22, 0.9) 100%); border: 1px solid rgba(173, 235, 179, 0.2); padding: 30px; border-radius: 16px; backdrop-filter: blur(20px); transition: all 0.4s cubic-bezier(0.23, 1, 0.320, 1); cursor: pointer; position: relative; overflow: hidden;">

<div style="font-size: 40px; margin-bottom: 15px; animation: icon-bounce 3s ease-in-out infinite 0.3s;">📚</div>
<h3 style="color: #ADEBB3; font-size: 22px; margin: 0 0 12px 0; font-weight: 700;">Learning Pro AI</h3>
<p style="color: #8DB896; font-size: 14px; line-height: 1.6; margin: 0;">Personalized adaptive learning platform leveraging LLMs. 3000+ users, 150K+ interactions tracked with ML optimization.</p>
<div style="display: flex; gap: 8px; margin-top: 15px; flex-wrap: wrap;">
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">LLM</span>
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">Personalization</span>
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">Full-Stack</span>
</div>
</div>

<!-- Project Card 3 -->
<div style="background: linear-gradient(135deg, rgba(26, 74, 46, 0.8) 0%, rgba(13, 31, 22, 0.9) 100%); border: 1px solid rgba(173, 235, 179, 0.2); padding: 30px; border-radius: 16px; backdrop-filter: blur(20px); transition: all 0.4s cubic-bezier(0.23, 1, 0.320, 1); cursor: pointer; position: relative; overflow: hidden;">

<div style="font-size: 40px; margin-bottom: 15px; animation: icon-bounce 3s ease-in-out infinite 0.6s;">🔐</div>
<h3 style="color: #ADEBB3; font-size: 22px; margin: 0 0 12px 0; font-weight: 700;">PC App Lock</h3>
<p style="color: #8DB896; font-size: 14px; line-height: 1.6; margin: 0;">Advanced security utility with facial recognition & encryption. 50K+ downloads with 4.8★ rating on trusted platforms.</p>
<div style="display: flex; gap: 8px; margin-top: 15px; flex-wrap: wrap;">
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">Security</span>
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">CV</span>
  <span style="background: rgba(173, 235, 179, 0.15); color: #ADEBB3; padding: 6px 12px; border-radius: 20px; font-size: 12px;">Desktop</span>
</div>
</div>

</div>

---

## 🛠️ Tech Stack Arsenal

<div style="padding: 40px 20px;">

<style>
  @keyframes float-in {
    0% { opacity: 0; transform: translateY(20px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  
  .tech-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 15px;
    margin: 30px 0;
  }
  
  .tech-item {
    background: linear-gradient(135deg, rgba(173, 235, 179, 0.08) 0%, rgba(74, 122, 85, 0.05) 100%);
    border: 1px solid rgba(173, 235, 179, 0.2);
    padding: 16px;
    border-radius: 12px;
    text-align: center;
    font-weight: 600;
    color: #ADEBB3;
    font-size: 13px;
    backdrop-filter: blur(10px);
    transition: all 0.3s ease;
    cursor: pointer;
  }
  
  .tech-item:hover {
    background: linear-gradient(135deg, rgba(173, 235, 179, 0.15) 0%, rgba(74, 122, 85, 0.1) 100%);
    border-color: rgba(173, 235, 179, 0.4);
    transform: translateY(-8px);
    box-shadow: 0 12px 30px rgba(173, 235, 179, 0.1);
  }
</style>

<h3 style="color: #ADEBB3; font-size: 18px; text-transform: uppercase; letter-spacing: 2px; margin-bottom: 10px;">Machine Learning & AI</h3>
<div class="tech-grid">
  <div class="tech-item">🤖 TensorFlow</div>
  <div class="tech-item">🔥 PyTorch</div>
  <div class="tech-item">🧠 scikit-learn</div>
  <div class="tech-item">🤗 HuggingFace</div>
  <div class="tech-item">⚡ Keras</div>
  <div class="tech-item">📈 LightGBM</div>
</div>

<h3 style="color: #ADEBB3; font-size: 18px; text-transform: uppercase; letter-spacing: 2px; margin: 30px 0 10px;">Data Engineering</h3>
<div class="tech-grid">
  <div class="tech-item">🐍 Python</div>
  <div class="tech-item">🐼 Pandas</div>
  <div class="tech-item">📊 NumPy</div>
  <div class="tech-item">🗄️ SQL</div>
  <div class="tech-item">🔗 PostgreSQL</div>
  <div class="tech-item">📉 Spark</div>
</div>

<h3 style="color: #ADEBB3; font-size: 18px; text-transform: uppercase; letter-spacing: 2px; margin: 30px 0 10px;">Visualization & Tools</h3>
<div class="tech-grid">
  <div class="tech-item">📊 Plotly</div>
  <div class="tech-item">🎨 Seaborn</div>
  <div class="tech-item">📈 Matplotlib</div>
  <div class="tech-item">📓 Jupyter</div>
  <div class="tech-item">🐙 GitHub</div>
  <div class="tech-item">☁️ Colab</div>
</div>

</div>

---

## 🎯 What I'm Building Right Now

<div style="padding: 40px 20px; background: linear-gradient(135deg, rgba(26, 74, 46, 0.3) 0%, rgba(74, 122, 85, 0.2) 100%); border-radius: 16px; border: 1px solid rgba(173, 235, 179, 0.2); margin: 40px 0;">

<style>
  .timeline-item {
    padding: 20px;
    border-left: 3px solid #ADEBB3;
    margin: 20px 0;
    position: relative;
    padding-left: 30px;
  }
  
  .timeline-item::before {
    content: '';
    position: absolute;
    left: -9px;
    top: 25px;
    width: 15px;
    height: 15px;
    border-radius: 50%;
    background: #ADEBB3;
    box-shadow: 0 0 0 5px rgba(173, 235, 179, 0.2);
  }
  
  .timeline-item h4 {
    color: #ADEBB3;
    margin: 0 0 8px 0;
    font-size: 16px;
  }
  
  .timeline-item p {
    color: #8DB896;
    margin: 0;
    font-size: 14px;
    line-height: 1.5;
  }
</style>

<h3 style="color: #ADEBB3; text-transform: uppercase; letter-spacing: 2px; font-size: 18px; margin-top: 0;">Current Focus</h3>

<div class="timeline-item">
  <h4>🚀 Advanced Deep Learning Pipeline</h4>
  <p>Building production-grade neural network architectures with real-time inference optimization and monitoring.</p>
</div>

<div class="timeline-item">
  <h4>📊 Multi-Modal Data Analysis Engine</h4>
  <p>Integrating vision, text, and audio ML models into unified platform for comprehensive data insights.</p>
</div>

<div class="timeline-item">
  <h4>🔬 Research Paper Implementation</h4>
  <p>Replicating cutting-edge ML papers and sharing detailed implementations on GitHub & technical blog.</p>
</div>

</div>

---

## 📈 Skills Heatmap

<div style="padding: 40px 20px;">

<style>
  .skill-bar {
    margin: 20px 0;
  }
  
  .skill-name {
    color: #ADEBB3;
    font-weight: 600;
    margin-bottom: 8px;
    display: flex;
    justify-content: space-between;
    font-size: 14px;
  }
  
  .skill-bar-container {
    height: 8px;
    background: rgba(173, 235, 179, 0.1);
    border-radius: 10px;
    overflow: hidden;
    border: 1px solid rgba(173, 235, 179, 0.2);
  }
  
  .skill-bar-fill {
    height: 100%;
    background: linear-gradient(90deg, #7FD18E 0%, #ADEBB3 100%);
    border-radius: 10px;
    transition: width 1.5s cubic-bezier(0.34, 1.56, 0.64, 1);
  }
</style>

<h3 style="color: #ADEBB3; text-transform: uppercase; letter-spacing: 2px; font-size: 18px; margin-top: 0;">Expertise Breakdown</h3>

<div class="skill-bar">
  <div class="skill-name"><span>Machine Learning Architecture</span> <span>92%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 92%;"></div></div>
</div>

<div class="skill-bar">
  <div class="skill-name"><span>Python & Data Processing</span> <span>95%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 95%;"></div></div>
</div>

<div class="skill-bar">
  <div class="skill-name"><span>NLP & Text Analytics</span> <span>85%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 85%;"></div></div>
</div>

<div class="skill-bar">
  <div class="skill-name"><span>Deep Learning & Neural Networks</span> <span>80%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 80%;"></div></div>
</div>

<div class="skill-bar">
  <div class="skill-name"><span>Data Visualization & Storytelling</span> <span>88%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 88%;"></div></div>
</div>

<div class="skill-bar">
  <div class="skill-name"><span>MLOps & Deployment</span> <span>72%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 72%;"></div></div>
</div>

<div class="skill-bar">
  <div class="skill-name"><span>SQL & Database Design</span> <span>84%</span></div>
  <div class="skill-bar-container"><div class="skill-bar-fill" style="width: 84%;"></div></div>
</div>

</div>

---

## 🌍 Let's Connect

<div style="padding: 40px 20px; text-align: center;">

<p style="color: #8DB896; font-size: 16px; margin-bottom: 25px;">Open to collaborations, discussions about ML, and exciting data science opportunities</p>

<style>
  .social-btn {
    display: inline-block;
    padding: 12px 28px;
    margin: 8px;
    border-radius: 50px;
    border: 2px solid #ADEBB3;
    color: #ADEBB3;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    font-size: 14px;
    text-transform: uppercase;
    letter-spacing: 1px;
    cursor: pointer;
  }
  
  .social-btn:hover {
    background: #ADEBB3;
    color: #0F2E1E;
    transform: translateY(-3px);
    box-shadow: 0 10px 25px rgba(173, 235, 179, 0.2);
  }
</style>

<div>
  <a href="https://github.com/StarkNitish" class="social-btn">GitHub</a>
  <a href="https://instagram.com/nitish_stark" class="social-btn">Instagram</a>
  <a href="https://youtube.com/channel/UCd93OmRn1xVRGCx3_qo1u4Q" class="social-btn">YouTube</a>
  <a href="mailto:contact@nitish.ai" class="social-btn">Email</a>
</div>

</div>

---

<div style="text-align: center; padding: 40px 20px; color: #8DB896; border-top: 1px solid rgba(173, 235, 179, 0.2);">
  <p style="margin: 10px 0; font-size: 14px;">
    <strong style="color: #ADEBB3;">Made with 💚 & crafted with precision</strong><br/>
    Building tomorrow's AI solutions, one algorithm at a time<br/>
    <em>© 2026 Nitish Kumar — Let's transform data into impact</em>
  </p>
</div>

</div>
