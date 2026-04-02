# HTML Sectioning 
==webpage එක **logical parts (sections)** වලට divide කිරීම==

Sectioning use කරන්නේ:
- webpage structure clear කරන්න
- SEO improve කරන්න
- readability improve කරන්න
- accessibility improve කරන්න (screen readers)
- large content organize කරන්න

![[sectioning.jpg]]

```
<body>

<header>
   <h1>My Blog</h1>
</header>

<nav>
   <a href="#">Home</a>
   <a href="#">Contact</a>
</nav>

<section>

   <article>
      <h2>HTML</h2>
      <p>HTML lesson</p>
   </article>

</section>

<aside>
   <p>Advertisement</p>
</aside>

<footer>
   <p>Copyright 2026</p>
</footer>

</body>
```


```
<body>

<header>
   website title
</header>

<nav>
   menu links
</nav>

<main>
   main content
</main>

<footer>
   footer details
</footer>

</body>
```

## Main Sectioning Tags

### header tag
==page header part==

use for:
- title
- logo
- navigation intro

```
<header>
   <h1>My Website</h1>
</header>
```

### nav tag
==navigation link==
menu links define කරනවා.
```
<nav>
   <a href="#">Home</a>
   <a href="#">About</a>
</nav>
```

### section tag
==related content group==
topic based content divide කරනවා.
```
<section>
   <h2>HTML Tutorial</h2>
   <p>HTML basics</p>
</section>
```

### article tag
==independent content part==
- blog post
- news article
- forum post
independent use කරන්න පුළුවන්.

```
<article>
   <h2>News Title</h2>
   <p>News description</p>
</article>
```

### aside tag
==side content==
- sidebar
- ads
- related info

```
<aside>
   <p>Related links</p>
</aside>
```

### footer tag
==bottom part==
```
<footer>
   <p>Copyright 2026</p>
</footer>
```

### main tag
==introduce in page එකේ most important information.==
`<main>` use කරන්නේ:
- page එකේ main topic content indicate කරන්න
- SEO improve කරන්න
- accessibility improve කරන්න
- page structure clear කරන්න
- repeated parts remove කරන්න (nav, footer etc)
```
<main>
   <h1>HTML Tutorial</h1>
   <p>HTML lesson content</p>
</main>
```

[[Table]]
