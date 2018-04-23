# Startpage theme for hugo

## Instructions:
Create data/links.yml in your site directory

This file takes the following format:

```yaml
---
- name: Some card title
  colour: blue # (a valid mdl color name)
  sections: # A section
  - links:
    - title: Google
      url: https://www.google.com
    - title: Bing
      url: https://www.bing.com/
  - links:
    - title: Hacker News
      url: https://news.ycombinator.com/
    - title: Reddit r/devops
      url: https://www.reddit.com/r/devops/
  - links:
    - title: Al Jazeera
      url: https://www.aljazeera.com/
```
