---
layout: about
title: About
permalink: /
# subtitle: # TODO: re-enable later, e.g. "Research Affiliate at MIT CSAIL · MS student at USC"

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p style="display: block; width: 100%; text-align: center;"><a href="mailto:ryandlindeborg@gmail.com">ryandlindeborg@gmail.com</a></p>

selected_papers: true # shows papers marked selected={true} from _bibliography/papers.bib
social: false # bottom social-icon row off; X + email live in the profile card above (set true to bring the row back)

announcements:
  enabled: false # TODO: set true once there are real news items in _news/
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I'm a Research Affiliate at MIT CSAIL, where I work with [Will Shen](https://shen.nz/), [Nishanth Kumar](https://nishanthjkumar.com/), [Leslie Kaelbling](https://people.csail.mit.edu/lpk/), and [Tomás Lozano-Pérez](https://people.csail.mit.edu/tlp/), and a master's student at USC, where I work with [Abrar Anwar](https://abraranwar.github.io/), [Jesse Zhang](https://www.jessezhang.net/), and [Jesse Thomason](https://jessethomason.com/). My research interests are in robot learning and aligning robot behavior with human intent.

Previously, I developed large-scale robotic systems at Amazon Robotics and graduated from Harvard.

<div class="bio-links"><a href="https://x.com/ryanlindeborg" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener"><i class="fa-brands fa-x-twitter"></i> Twitter</a></div>

<style>
  /* breathing room above the Research section and between papers */
  .research-heading {
    margin-top: 2.5rem;
  }
  .publications ol.bibliography > li {
    margin-bottom: 2rem;
  }
  /* research section: larger title, grey co-authors (own name stays bold + full contrast) */
  .publications .title {
    font-size: 1.35rem;
  }
  .publications .author {
    color: #6b6b6b;
  }
  .publications .author strong {
    color: var(--global-text-color);
  }
  /* grey venue line; description keeps full contrast; small gap above both */
  .publications .periodical {
    color: #6b6b6b;
    margin-top: 0.5rem;
  }
  .publications .periodical em {
    color: inherit; /* the theme styles <em> directly, which would override the grey */
  }
  .publications .periodical.pub-note {
    color: var(--global-text-color);
  }
  /* presentation designation (e.g. Spotlight) in the venue line */
  .publications .periodical .presentation-label {
    color: #c0392b;
    font-weight: bold;
  }
  /* slightly larger link buttons (theme default is 0.88rem), with a gap above the row */
  .publications .links {
    margin-top: 0.75rem;
  }
  /* softened buttons: rounded corners, hairline border, gentle tinted hover
     (selector matches the theme's own specificity so the border override wins) */
  .publications ol.bibliography li .links a.btn,
  .bio-links a.btn {
    margin-left: 0; /* the base .btn rule adds 0.375rem all around, which misaligns the left edge */
    font-size: 0.9rem;
    color: var(--global-text-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 0.25rem 1rem;
    transition: all 0.2s ease-in-out;
  }
  .publications ol.bibliography li .links a.btn:hover,
  .bio-links a.btn:hover {
    color: var(--global-theme-color);
    border-color: var(--global-theme-color);
    background-color: color-mix(in srgb, var(--global-theme-color) 7%, transparent);
    text-decoration: none;
  }
</style>
