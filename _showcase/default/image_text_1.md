---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---
<div>
  <img data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" class="lazy w-100 rounded-xl" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">

  <div class="card-img-overlay" style="overflow: scroll; background: rgb(255,255,255,0.8)">
    <h5 class="card-title">Youtube Video Classification and NLP Analysis</h5>
    <p class="card-text">
      This project involved scraping YouTube videos related to computer games from January to June 2024 using the YouTube API. I then trained and utilized a BERT model to analyze the game genres featured in the videos. Through this analysis, I identified the most popular game genre. Next, I used the OpenAI API to analyze the comments of the most popular video within that genre and performed sentiment analysis to assess people's attitudes toward both the video and the game.
    </p>
    <p class="card-text">
      {% raw %}
      <code>&lt;img data-src=&quot;[Image URL]&quot; class=&quot;lazy w-100 rounded-xl&quot; src=&quot;{{ '/assets/images/empty_300x200.png' | relative_url }}&quot;&gt;</code>
      {% endraw %}
    </p>
  </div>
</div>
