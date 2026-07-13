# Daily Learning
## Morning Planning
- [ ] Check out the [github blog](http://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](http://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](http://www.ffmpeg.org)
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:staturation=1.1" output.mp4
```
