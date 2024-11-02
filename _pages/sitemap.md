---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---
<div class="custom-line"></div>

<style>
/* Stylish List Styles */

.stylish-list {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin: 0;
  padding: 0;
}

.stylish-list .list-item {
  display: flex;
  align-items: center;
  background-color: #f9f9f9;
  border-radius: 10px;
  padding: 15px;
  transition: background-color 0.3s ease;
}

.stylish-list .item-icon {
  flex: 0 0 60px;
  margin-right: 15px;
}

.stylish-list .item-icon img {
  width: 60px;
  height: 60px;
  object-fit: cover;
  border-radius: 50%;
}

.stylish-list .item-content h3 {
  margin: 0;
  font-size: 1.2em;
}

.stylish-list .item-content h3 a {
  text-decoration: none;
  color: #333;
}

.stylish-list .item-content p {
  margin: 5px 0 0;
  color: #666;
}

.stylish-list .list-item:hover {
  background-color: #eaeaea;
}

.stylish-list .item-content h3 a:hover {
  color: #007acc;
}

@media (max-width: 600px) {
  .stylish-list .list-item {
    flex-direction: column;
    align-items: flex-start;
  }

  .stylish-list .item-icon {
    margin-bottom: 10px;
  }
}
.custom-line {
  width: 4.5%;
  height: 5px; /* Adjust thickness here */
  background-color: #F27380; /* Replace with your specific red color */
  border-radius: 3px; /* Half of the height for fully rounded ends */
  margin: 0px left; /* Space above and below the line */
  margin-top: 0px; /* Space above the line */
  margin-bottom: 15px; /* Space below the line */
} 
</style>

<div class="stylish-list">
  {% assign specific_pages = site.pages | where: "include_in_list", true %}
  {% for page in specific_pages %}
    <div class="list-item">
      {% if page.icon %}
        <div class="item-icon">
          <img src="{{ page.icon }}" alt="{{ page.title }} icon">
        </div>
      {% endif %}
      <div class="item-content">
        <h3><a href="{{ page.url | relative_url }}">{{ page.title }}</a></h3>
        {% if page.description %}
          <p>{{ page.description }}</p>
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>