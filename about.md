---
layout: default
title: About
permalink: /about/
---

<div class="page">
    <div class="wrapper">
        <h1>About Me</h1>
        
        <div class="about-page-content">
            <div class="about-image">
                <img src="{{ '/assets/images/profile.jpg' | relative_url }}" 
                     alt="Pengyu Zha"
                     onerror="this.src='data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 width=%27300%27 height=%27300%27%3E%3Crect fill=%27%23ddd%27 width=%27300%27 height=%27300%27/%3E%3Ctext fill=%27%23999%27 font-family=%27sans-serif%27 font-size=%2740%27 dy=%2710.5%27 font-weight=%27bold%27 x=%2750%25%27 y=%2750%25%27 text-anchor=%27middle%27%3EPZ%3C/text%3E%3C/svg%3E'">
            </div>
            
            <div class="about-text">
                <h2>Pengyu Zha (查鹏宇)</h2>
                
                <p>
                    I'm an undergraduate student at <strong>Shenzhen University</strong>, pursuing 
                    a degree in Computer Science. My academic journey has led me to develop a 
                    deep interest in computer vision and artificial intelligence.
                </p>
                
                <h3>Education</h3>
                <ul>
                    <li>
                        <strong>Bachelor of Science in Computer Science</strong><br>
                        Shenzhen University<br>
                        <em>Present</em>
                    </li>
                </ul>
                
                <h3>Research Interests</h3>
                <p>
                    My research interests primarily focus on <strong>Computer Vision</strong>, 
                    including but not limited to:
                </p>
                <ul>
                    <li>Image Classification and Recognition</li>
                    <li>Object Detection and Segmentation</li>
                    <li>Deep Learning for Visual Understanding</li>
                    <li>Convolutional Neural Networks (CNNs)</li>
                    <li>Transfer Learning and Few-shot Learning</li>
                </ul>
                
                <h3>Contact</h3>
                <p>
                    Feel free to reach out to me if you'd like to discuss research opportunities, 
                    collaborations, or have any questions. I'm always open to connecting with 
                    fellow researchers and students in the field.
                </p>
                <p>
                    <i class="fas fa-envelope"></i> Email: {{ site.email }}<br>
                    <i class="fab fa-github"></i> GitHub: 
                    <a href="https://github.com/{{ site.social.github }}" target="_blank">
                        {{ site.social.github }}
                    </a>
                </p>
            </div>
        </div>
    </div>
</div>

