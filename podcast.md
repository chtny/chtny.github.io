---
layout: default
title: Podcast
permalink: /podcast/
---
Weekly short episodes for the highs and lows; small yet impactful ideas. Occasional long candid conversations with guests.

- [Apple Podcasts](https://podcasts.apple.com/podcast/id1511066766)
- [Spotify](https://open.spotify.com/show/0Ag9bNP2x2ova48QpnzSEy)
- [Pocket Casts](https://pca.st/rfr5tkab)
- [Overcast](https://overcast.fm/itunes1511066766)
- [Listen on my website](https://chaitanya.page/podcast/)
- [RSS Feed](https://chaitanya.page/feed/podcast)

<h2>Latest episodes:</h2>
          <section>
            {% for post in site.categories[podcast] %}
              <article">
                <p>
                {% if site.date_format %}
                    {{ post.date | date: site.date_format }}
                {% else %}
                    {{ post.date | date: "%b %-d, %Y" }}
                {% endif %}
               </p>
                <a href="{{ post.url | relative_url }}">
                  <h3>{{ post.title }}</h3>
                </a>
              </article>
						{% endfor %}
          </section>