---
layout: page
permalink: /life_outside_data/
title: life outside data
description: A sample of my interests outside the world of data.
nav: false
nav_order: 7
display_categories: [Travel, Books, TV and movies, Music]
horizontal: false
toc:
  sidebar: left
---

{% if page.display_categories contains "Travel" %}

<section>
    <h1>Travel</h1>
    <p>I'm a keen traveller and enjoy seeing different cultures and foods from other places. I've been fortunate in having being able to travel to many places, including some as part of my PhD travels. Some of my personal highlights of my travels have included the Southern USA, Tokyo, Munich, and Rome. </p>
    <div class="l-page">
        <iframe src="{{ '/assets/folium/travel_map.html' | relative_url }}" frameborder='0' scrolling='no' height="500px" width="100%" style="border: 1px dashed grey;"></iframe>
    </div>

    {% details Generating the map %}
    The above map is generated using the [folium package](https://python-visualization.github.io/folium/latest/getting_started.html) and can be altered by changing the information in `assets/folium/travel_map_data.csv` and running `generate_travel_map.py`.
    {% enddetails %}

</section>
{% endif %}

{% if page.display_categories contains "Books" %}

<section>
    <h1>Books</h1>
    <p>I've always enjoyed esponiage novels, alongside fantasty and thrillers, and bits and pieces of non-fiction. I have a
    <a
    href="https://www.goodreads.com/user/show/46128883-conor-hamill" rel="external nofollow noopener" target="_blank">Goodreads account</a> and a <a
    href="https://app.thestorygraph.com/profile/conor_hamill" rel="external nofollow noopener" target="_blank"> Storygraph account</a> which are really just collections of things I've read and want to read. Some of my personal favourites are below.</p>

<h2>Thrillers and crime</h2>
<ul>
  <li><strong>Steve Cavanagh</strong>
    <ul>
      <li> Thirteen <em>(one of the best thrillers I've read)</em></li>
    </ul>
  </li>
  <li><strong>Lee Child</strong>
    <ul>
      <li> Jack Reacher <em>(who thought a guy beating up goons again and again could be exhilarating?)</em></li>
    </ul>
  </li>
  <li><strong>Ian Rankin</strong>
    <ul>
      <li> Anything with Rebus, but The Falls is the book I've read that best captures Edinburgh</li>
    </ul>
  </li>
</ul>

<h2>Fantasy and sci-fi</h2>
<ul>
  <li><strong>Philip Pullman</strong>
    <ul>
      <li> His Dark Materials</li>
      <li> The Book of Dust</li>
    </ul>
  </li>
  <li><strong>Frank Herbert</strong>
    <ul>
      <li> Dune</li>
      <li> Dune Messiah <em>(my personal Dune where-to-stop-reading opinion is here, where you can convince yourself of a conclusive ending. Denis Villeneuve may feel the same.)</em></li>
    </ul>
  </li>
  <li><strong>Andy Weir</strong>
    <ul>
      <li> The Martian</li>
      <li> Project Hail Mary <em>(a shameless tribute to the collaboration of scientists and engineers)</em></li>
    </ul>
  </li>
  <li><strong>J.R.R. Tolkien</strong>
    <ul>
      <li> The Hobbit</li>
      <li> The Lord of the Rings</li>
      <li> The Children of Hurin <em>(the most Shakespearean tragedy ever to grace the fantasy genre)</em></li>
    </ul>
  </li>
  <li><strong>George R.R. Martin</strong>
    <ul>
      <li> A Song of Ice and Fire</li>
      <li> Fevre Dream <em>(never thought much of vampires, but this is a strong historical fiction)</em></li>
    </ul>
  </li>
  <li><strong>Susanna Clarke</strong>
    <ul>
      <li> Jonathan Strange & Mr Norrell</li>
      <li> Piranesi</li>
    </ul>
  </li>
</ul>

<h2>Horror</h2>
<ul>
  <li><strong>Stephen King</strong>
    <ul>
      <li> 11/22/63 <em>(my personal favorite interpretation of time travel in a book)</em></li>
      <li> IT <em>(a book about how you grow up and forget your childhood but it never leaves you, fear, small-town bigotry, and lots of other things)</em></li>
      <li> The Shining</li>
      <li> The Stand</li>
      <li> Pet Sematary <em>(King's most horrifying)</em></li>
    </ul>
  </li>
</ul>

<h2>Other fiction</h2>
<ul>
  <li><strong>Douglas Adams</strong>
    <ul>
      <li> The Hitchhiker's Guide to the Galaxy <em>(mandatory reading for life in my opinion)</em></li>
    </ul>
  </li>
  <li><strong>John le Carré</strong>
    <ul>
      <li> The Spy Who Came in from the Cold <em>(if you're looking to try out le Carré, this is where to start)</em></li>
      <li> Tinker, Tailor, Soldier, Spy</li>
      <li> Smiley's People <em>(read TTSS first, these are two of the few Smiley books that need to be read in order)</em></li>
      <li> A Perfect Spy <em>(would recommend after reads of other le Carré books. Feels like the most personal of all his books)</em></li>
    </ul>
  </li>
  <li><strong>Chimamanda Ngozi Adichie</strong>
    <ul>
      <li> Half of a Yellow Sun <em>(horrific fiction of Nigeria's civil war)</em></li>
    </ul>
  </li>
  <li><strong>Joseph Heller</strong>
    <ul>
      <li> Catch 22 <em>(funniest book that bares the irrationality of war more than any documentary or thesis ever could)</em></li>
    </ul>
  </li>
  <li><strong>John Steinbeck</strong>
    <ul>
      <li> Grapes of Wrath</li>
      <li> Of Mice and Men</li>
    </ul>
  </li>
</ul>

<h2>Non-fiction</h2>
<ul>
  <li><strong>Ben McIntyre</strong>
    <ul>
      <li> The Spy and the Traitor</li>
      <li> A Spy among Friends</li>
    </ul>
  </li>
  <li><strong>Chris Miller</strong>
    <ul>
      <li> Chip War</li>
    </ul>
  </li>
  <li><strong>David Spiegelhalter</strong>
    <ul>
      <li> The Art of Statistics <em>(the book that made me appreciate Bayesian statistics)</em></li>
    </ul>
  </li>
  <li><strong>David McKittrick and David McVea</strong>
    <ul>
      <li> Making Sense of the Troubles <em>(a great factual and balanced overview of conflict in Northern Ireland)</em></li>
    </ul>
  </li>
  <li><strong>Patrick Radden Keefe</strong>
    <ul>
      <li> Say Nothing <em>(provides a nuanced view of the conflict and its aftermath)</em></li>
    </ul>
  </li>
</ul>

</section>
{% endif %}

<!-- {% if page.display_categories contains "TV and movies" %}
<section>
    <h1>Tv and movies</h1>
    <p>This is the text for the tv and movies section.</p>
</section>
{% endif %}

{% if page.display_categories contains "Music" %}
<section>
    <h1>Music</h1>
    <p>This is the text for the music section.</p>
</section>
{% endif %} -->
