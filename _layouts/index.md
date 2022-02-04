<!DOCTYPE html>
<html lang="en">
<head>
    <title>{% if page.title %}{{ page.title }} | Berry Empire{% else %}Berry Empire{% endif %}</title>
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@200;400;600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="/style.css">
    <meta name="description" content="{% if page.title %}{{ page.title }} | Berry Empire{% else %}Berry Empire{% endif %}">
    <meta property="og:description" content="{% if page.title %}{{ page.title }} | Berry Empire{% else %}Berry Empire{% endif %}">
    <meta property="og:title" content="{% if page.title %}{{ page.title }} | Berry Empire{% else %}Berry Empire{% endif %}">
    <meta property="og:type" content="web" />
    <meta property="og:url" content="{{site.url}}{{page.url}}" />
    <meta property="og:image" content="https://berryempire.cupertinoalliance.ca/images/ogp.png" />
    <meta name="theme-color" content="#f01030">
    <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body class="index">
    <header>
        <a class="logo" href="/">
            <span>Berry Empire</span>
            <span>Glory to the Emperor</span>
        </a>
    </header>
<div class="news">
   {% include news.html %}
</div>
    <main>
      {{content}}
    </main>
    <footer>
        <div class="links">
            <a class="thickbutton thick positive" target="_blank" href="/best/"><span>Space program</span></a>
            <a class="thickbutton thick positive" target="_blank" href="/press"><span>Press</span></a>
            <a class="thickbutton thick positive" target="_blank" href="/citizenship"><span>Citizenship</span></a>
            <a class="thickbutton thick positive" target="_blank" href="mailto:empire@duck.com"><span>Email</span></a>
            <a class="thickbutton thick positive" target="_blank" href="/law/"><span>Law</span></a>
            <a class="thickbutton thick positive" target="_blank" href="/law/constitution.html"><span>Constitution</span></a>
            <a class="thickbutton thick positive" target="_blank" href="https://micronations.wiki/wiki/Berry_Empire"><span>Wiki</span></a>
            <a class="thickbutton thick positive" target="_blank" href="https://instagram.com/berryempire_gov"><span>Instagram</span></a>
            <a class="thickbutton thick positive" target="_blank" href="https://discord.gg/GPzvUDccRX"><span>Discord</span></a>
            <a class="thickbutton thick positive" target="_blank" href="https://micronear.cupertinoalliance.ca/micronation.html?m=RR"><span>Micronear</span></a>
        </div>
        <div class="copyright">
            <p>&copy; Copyright, Berry Empire, 2020 - 2022. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
