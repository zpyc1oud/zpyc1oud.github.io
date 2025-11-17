---
layout: default
title: Contact
permalink: /contact/
---

<div class="page">
    <div class="wrapper">
        <h1>Contact</h1>
        
        <div class="contact-content">
            <p>
                I'm always interested in connecting with fellow researchers, collaborators, 
                and students. Feel free to reach out if you'd like to discuss research 
                opportunities, collaborations, or simply connect!
            </p>
            
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <div>
                        <h3>Email</h3>
                        <p>
                            <a href="mailto:{{ site.email }}">{{ site.email }}</a>
                        </p>
                    </div>
                </div>
                
                <div class="contact-item">
                    <i class="fab fa-github"></i>
                    <div>
                        <h3>GitHub</h3>
                        <p>
                            <a href="https://github.com/{{ site.social.github }}" target="_blank">
                                github.com/{{ site.social.github }}
                            </a>
                        </p>
                    </div>
                </div>
                
                <div class="contact-item">
                    <i class="fas fa-university"></i>
                    <div>
                        <h3>Institution</h3>
                        <p>{{ site.author.affiliation }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

