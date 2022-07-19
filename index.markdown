---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

On July 12th, my Dad was airlifted to Massachussets General Hospital here in Boston
with heart problems. I am repurposing my website to serve as a place where we can
post updates about his health. Once this is resolved, I'll remove this header and 
post some CS stuff :)

Here is a list of posts about his cardiac situation:

<ul>
  {% for post in site.categories.dad-cardiac %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

---

Welcome!

This is a repository for a few migrated posts from an old blog, along with links to my [GitHub](https://github.com/liam-strand), [YouTube](https://www.youtube.com/c/LiamStrand/featured), and [SoundCloud](https://soundcloud.com/liam_itchy_dad) accounts where you will find samples of some of my recent and past work, and interests.

I am a rising junior studying computer science at the Tufts School of Engineering. I love solving complex problems and care deeply in my role as a TA about helping students have an exciting and welcoming first step into computer science. Although I have become enamored with Erlang, I am doing most of my current work in Python and C++, and dabbling in Rust and TypeScript.

Outside of my life as a developing engineer, I split my time between family homes on the East and West coasts, where I am often coerced into home repair projects. I enjoy hiking and spending time on the water. Theatre is fortunately still in my life throughout the year as a reader/judge for a Summer Short Play Festival. I also get lots of pleasure from cooking and baking for others, and from reading almost anything alongside Bela, my unpredictable dog.

Liam

![Bela](/assets/images/bela.jpeg)
