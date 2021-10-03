---
layout: default
---
I'm Jeonghyeon Lee, and I develop software. I thought I could write something more than just code. You can find the navigation bar at the top of the page.

{% capture included_resume %}{% include_relative resume.md %}{% endcapture %}

## [Resume](/resume)
{{ included_resume | markdownify }}

