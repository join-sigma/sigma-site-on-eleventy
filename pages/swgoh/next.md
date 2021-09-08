---
layout: layouts/page.njk
title: Sigma Next
permalink: /swgoh/next.html
section: SWGOH
date: 2018-01-01
parent: Gaming communities
eleventyNavigation:
  key: Sigma Next
  parent: SWGOH
#   order: 3
---

## Our NEXT generation

The SIGMA Alliance is a multi-guild SWGOH community focused on a unified “ONE GUILD” mentality, and a performance driver system of player movement. SIGMA has been around since the beginning of SWGOH and currently houses a large array of guildsl Our structure promotes the sense of a single community, designed to help members grow to their fullest potential. 

We’ve always embraced the pursuit of developmental guilds, and enjoyed bringing new players into the game. SIGMA NEXT is the evolution of that pursuit, and a great place to start your climb within the SIGMA ranks as a new SWGoH player. We’ve got top notch leadership and guidance, that focuses on the investment in players in order to help everyone grow and prosper within the game and the community.

While an organization grows and prospers there is often a tendency to forget the fundamentals of what made that group possible in the first place. NEXT is our reminder that new players are at the core of those fundamental principles and it is an extension of Sigma that we pursue with excitement and passion. 

Join us today, make Sigma your home, and help us continue developing a community we can all be proud of together!

<!-- 
### Sigma NEXT Guilds

All Sigma NEXT guilds have two simple requirements: active Discord & swgoh.gg profile.

<ul>
{% for guilds in site.guilds-next  %}
      <li style="list-style: none; position: relative; margin-top: 0; padding-top: 0; margin-bottom: 3rem;">
        <a href=" {{ guilds-next.url }} " style="background: url({{ guilds-next.guild-photo}}) no-repeat bottom center; 
  background-size: cover;
  display: block;
  width: 100%;
  height: 26rem;">
			<p style="position: absolute; bottom: 0;  margin-bottom: 0; padding: 1rem; background-color: rgba(0,0,0,.5); width: 100%; color: white;">{{ guilds-next.short-description }}</p>
		</a>
      </li>
{% endfor %}
</ul>
 -->

{% include components/joinus.njk, type: "next" %}