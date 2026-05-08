---
layout: single
permalink: /
title: "Dongmyoung Lee"
excerpt: "Dongmyoung Lee — Postdoctoral Researcher at TU Wien working on dexterous robotic manipulation, deformable object manipulation, robot hand design, tactile sensing, and human-robot interaction."
author_profile: false
classes: wide
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-hero {
  display: grid;
  grid-template-columns: 190px 1fr;
  gap: 2rem;
  align-items: center;
  margin-top: 1rem;
  margin-bottom: 2rem;
}

.home-hero img {
  width: 180px;
  height: 180px;
  border-radius: 999px;
  object-fit: cover;
}

.home-hero h1 {
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 2.0rem;
}

.home-hero p {
  font-size: 1.02rem;
  line-height: 1.65;
}

.home-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1rem;
}

.home-btn {
  display: inline-block;
  padding: 0.45rem 0.85rem;
  border: 1px solid #d0d7de;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.9rem;
}

.home-btn:hover {
  text-decoration: none;
  background: #f6f8fa;
}

.news-list li {
  margin-bottom: 0.45rem;
}

.pub-card {
  display: grid;
  grid-template-columns: 185px 1fr;
  gap: 1.25rem;
  margin: 1.7rem 0;
  align-items: start;
}

.pub-card img {
  width: 185px;
  height: 115px;
  object-fit: contain;
  object-position: center;
  background: #ffffff;
  padding: 0.25rem;
  border-radius: 8px;
  border: 1px solid #eaecef;
}

.pub-card h3 {
  margin-top: 0;
  margin-bottom: 0.25rem;
  font-size: 1.05rem;
}

.pub-card p {
  margin: 0.25rem 0;
  line-height: 1.45;
}

.pub-links {
  margin-top: 0.55rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
}

.pub-links a {
  display: inline-flex;
  align-items: center;
  gap: 0.28rem;
  font-size: 0.92rem;
  text-decoration: none;
}

.pub-links a:hover {
  text-decoration: underline;
}

.pub-links i {
  font-size: 0.95rem;
}

@media (max-width: 720px) {
  .home-hero,
  .pub-card {
    grid-template-columns: 1fr;
  }

  .home-hero img,
  .pub-card img {
    width: 100%;
    max-width: 240px;
    height: auto;
    max-height: 150px;
    object-fit: contain;
  }
}
</style>

<div class="home-hero">
  <img src="/images/Profile_Dongmyoung.jpg" alt="Dongmyoung Lee">

  <div>
    <h1>Hello, I'm Dongmyoung Lee</h1>

    <p>
      I am a Postdoctoral Researcher at the
      <a href="https://www.tuwien.at/en/etit/ict/asl">Autonomous Systems Lab</a>,
      <a href="https://www.tuwien.at/">TU Wien</a>.
      My research focuses on dexterous robotic manipulation, deformable object manipulation,
      robot hand design and control, multimodal perception, and human-robot interaction.
    </p>

    <p>
      I completed my PhD at the
      <a href="https://www.imperial.ac.uk/robot-intelligence/">Robot Intelligence Lab</a>,
      <a href="https://www.imperial.ac.uk/">Imperial College London</a>,
      advised by Dr. Petar Kormushev and Dr. Nicolas Rojas.
    </p>

    <div class="home-links">
      <a class="home-btn" href="/files/CV_DongmyoungLee.pdf">CV</a>
      <a class="home-btn" href="https://scholar.google.com/citations?user=nufM4CwAAAAJ&hl=en">Scholar</a>
      <a class="home-btn" href="https://www.linkedin.com/in/dongmyoung-lee">LinkedIn</a>
    </div>
  </div>
</div>

---

## News

<ul class="news-list">
  <li><strong>2026:</strong> DexTwist was accepted to IEEE ARSO 2026.</li>
  <li><strong>2026:</strong> Our work on bimanual cloth manipulation with vision-based tactile sensing was submitted to IEEE Transactions on Mechatronics (T-Mech) </li>
  <li><strong>2025:</strong> GraphGarment was accepted to IEEE/RSJ IROS 2025.</li>
  <li><strong>2025:</strong> A Backbone for Long-Horizon Robot Task Understanding was published in IEEE Robotics and Automation Letters.</li>
  <li><strong>2024:</strong> G.O.G. was published in IEEE Robotics and Automation Letters and presented at IEEE/RSJ IROS 2024.</li>
  <li><strong>2024:</strong> Synthetic Data Enables Faster Annotation and Robust Segmentation for Multi-Object Grasping in Clutter was accepted to IEEE ICMRE 2024.</li>
  <li><strong>2024:</strong> A Soft Continuum Robot With Self-Controllable Variable Curvature was published in IEEE Robotics and Automation Letters and presented at RoboSoft 2024.</li>
  <li><strong>2023:</strong> Learning to Grasp Clothing Structural Regions for Garment Manipulation Tasks was accepted to IEEE/RSJ IROS 2023.</li>
  
</ul>

---

## Publications

<div class="pub-card">
  <img src="/images/touchgog.jpg" alt="Learning Bimanual Cloth Manipulation with Vision-based Tactile Sensing via Single Robotic Arm">
  <div>
    <h3>Learning Bimanual Cloth Manipulation with Vision-based Tactile Sensing via Single Robotic Arm</h3>
    <p><strong>Dongmyoung Lee</strong>, Wei Chen, Xiaoshuai Chen, Rui Zong, and Petar Kormushev</p>
    <p><em>IEEE Transactions on Mechatronics, submitted, 2026</em></p>
    <p>Vision-based tactile perception and control for bimanual cloth manipulation using a single robotic arm.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2603.10609" target="_blank" rel="noopener">
        <i class="fas fa-file-pdf" aria-hidden="true"></i> Paper
      </a>
      <a href="https://www.youtube.com/watch?v=Qom3WtHvSNI" target="_blank" rel="noopener">
        <i class="fas fa-video" aria-hidden="true"></i>Video
      </a>
      <a href="https://sites.google.com/view/touchgog/home" target="_blank" rel="noopener">
        <i class="fas fa-globe" aria-hidden="true"></i> Project Page
      </a>
    </div>
  </div>
</div>

<div class="pub-card">
  <img src="/images/dextwist.png" alt="DexTwist">
  <div>
    <h3>DexTwist: Dexterous Hand Retargeting for Twist Motion via Mixed Reality-based Teleoperation</h3>
    <p><strong>Dongmyoung Lee</strong>*, Chengxi Li*, and Dongheui Lee</p>
    <p><em>IEEE International Conference on Advanced Robotics and its Social Impacts, ARSO 2026</em></p>
    <p>Dexterous hand retargeting for twist motion through mixed-reality-based teleoperation.</p>
  </div>
</div>

<div class="pub-card">
  <img src="/images/gog.jpg" alt="G.O.G.">
  <div>
    <h3>G.O.G: A Versatile Gripper-On-Gripper Design for Bimanual Cloth Manipulation with a Single Robot Arm</h3>
    <p><strong>Dongmyoung Lee</strong>*, Wei Chen*, Xiaoshuai Chen, and Nicolas Rojas</p>
    <p><em>IEEE Robotics and Automation Letters, presented at IROS 2024</em></p>
    <p>A versatile gripper-on-gripper design enabling bimanual-style cloth manipulation with a single robot arm.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2401.10702.pdf" target="_blank" rel="noopener">
        <i class="fas fa-file-pdf" aria-hidden="true"></i> Paper
      </a>
      <a href="https://www.youtube.com/watch?v=YOI2AswGpAU" target="_blank" rel="noopener">
        <i class="fas fa-video" aria-hidden="true"></i>Video
      </a>
      <a href="https://sites.google.com/view/gripperongripper" target="_blank" rel="noopener">
        <i class="fas fa-globe" aria-hidden="true"></i> Project Page
      </a>
    </div>
  </div>
</div>

<div class="pub-card">
  <img src="/images/softrobot.png" alt="Soft Robotic Arm">
  <div>
    <h3>A Soft Continuum Robot With Self-Controllable Variable Curvature</h3>
    <p>Xinran Wang, Qiujie Lu, <strong>Dongmyoung Lee</strong>, Zhongxue Gan, and Nicolas Rojas</p>
    <p><em>IEEE Robotics and Automation Letters, presented at RoboSoft 2024</em></p>
    <p>A soft continuum robot which is capable of self-controlling continuously its curvature at the segment level.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2401.01739" target="_blank" rel="noopener">
        <i class="fas fa-file-pdf" aria-hidden="true"></i> Paper
      </a>
      <a href="https://www.youtube.com/watch?v=H6SCK0NjGpE" target="_blank" rel="noopener">
        <i class="fas fa-video" aria-hidden="true"></i>Video
      </a>
    </div>
  </div>
</div>

<div class="pub-card">
  <img src="/images/fruitgrasp.jpg" alt="Synthetic Data Enables Faster Annotation and Robust Segmentation">
  <div>
    <h3>Synthetic Data Enables Faster Annotation and Robust Segmentation for Multi-Object Grasping in Clutter</h3>
    <p><strong>Dongmyoung Lee</strong>, Wei Chen, and Nicolas Rojas</p>
    <p><em>IEEE International Conference on Mechatronics and Robotics Engineering, ICMRE 2024</em></p>
    <p>Synthetic data generation for faster annotation and robust segmentation in cluttered multi-object grasping scenes.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2401.13405.pdf" target="_blank" rel="noopener">
        <i class="fas fa-file-pdf" aria-hidden="true"></i> Paper
      </a>
      <a href="https://www.youtube.com/watch?v=V3SSSPSo-HY" target="_blank" rel="noopener">
        <i class="fas fa-video" aria-hidden="true"></i>Video
      </a>
      <a href="https://sites.google.com/view/synthetic-dataset-generation" target="_blank" rel="noopener">
        <i class="fas fa-globe" aria-hidden="true"></i> Project Page
      </a>
    </div>
  </div>
</div>

<div class="pub-card">
  <img src="/images/iros2023.png" alt="Learning to Grasp Clothing Structural Regions">
  <div>
    <h3>Learning to Grasp Clothing Structural Regions for Garment Manipulation Tasks</h3>
    <p>Wei Chen, <strong>Dongmyoung Lee</strong>, Digby Chappell, and Nicolas Rojas</p>
    <p><em>IEEE/RSJ International Conference on Intelligent Robots and Systems, IROS 2023</em></p>
    <p>Learning structural grasping regions for garment manipulation tasks.</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2306.14553.pdf" target="_blank" rel="noopener">
        <i class="fas fa-file-pdf" aria-hidden="true"></i> Paper
      </a>
      <a href="https://www.youtube.com/watch?v=Ik8mNMNgOvY" target="_blank" rel="noopener">
        <i class="fas fa-video" aria-hidden="true"></i>Video
      </a>
    </div>
  </div>
</div>
