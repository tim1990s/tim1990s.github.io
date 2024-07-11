---
layout: default
title: Home
---

<style>
  .profile-container {
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
    padding: 20px;
    border-radius: 10px;
    max-width: 900px;
    margin: auto;
    color: #333;
  }
  .profile-header {
    display: flex;
    align-items: center;
  }
  .profile-photo {
    flex: 0 0 auto;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    overflow: hidden;
    margin-right: 20px;
  }
  .profile-photo img {
    width: 100%;
    height: auto;
  }
  .profile-info {
    flex: 1;
  }
  .profile-info h1 {
    font-size: 2em;
    margin: 0;
  }
  .profile-info p {
    margin: 5px 0;
  }
  .profile-info .location {
    color: #555;
  }
  .profile-stats {
    display: flex;
    align-items: center;
    margin-top: 10px;
  }
  .profile-stats .followers {
    margin-right: 15px;
    font-weight: bold;
  }
  .profile-stats .connections {
    color: #0073b1;
  }
  .contact-info a {
    color: #0073b1;
    text-decoration: none;
  }
  .actions {
    display: flex;
    margin-top: 20px;
  }
  .actions button {
    background-color: #0073b1;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    margin-right: 10px;
    cursor: pointer;
  }
  .actions button.more {
    background-color: #ddd;
    color: #333;
  }
</style>

<div class="profile-container">
  <div class="profile-header">
    <div class="profile-photo">
      <img src="images/avata.jpg" alt="Profile Photo">
    </div>
    <div class="profile-info">
      <h1>Tim Nguyen</h1>
      <p>Senior Software Engineer</p>
      <p class="location">Ho Chi Minh City, Vietnam · <a href="mailto:mr.phucnguyen@hotmail.com">Contact info</a></p>
    </div>
  </div>
  <div class="actions">
    <a href="https://www.linkedin.com/in/timnguyen90s/"><button>Linkedin</button></a>
    <a href="https://github.com/tim1990s"><button>Github</button></a>
    <a href="https://x.com/NPhuc90"><button>Twitter</button></a>
    <a href="https://np90s.wordpress.com/who-am-i/"><button>WordPress</button></a>
    <a href="https://500px.com/p/np90s"><button class="more">500px</button></a>
  </div>
</div>


## Blog
Check out my [blog posts](blogs.md) for more insights and articles.
