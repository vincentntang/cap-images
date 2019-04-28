## Cap Images

Temporary Readme Placeholder

Things I had to google search for in order

- "Thesaurus word for Grid" - so I don't overlap namespaces with CSS Grid
- "Thesaurus word for Image" - so I don't overlap namespaces with images
- "Transparent images free"
- "Optimal ImageMagick compression and resizing"
- "Process env dotconfig file react"
- "HTML image tag name"
- "CSS grid by example"
- "Scss mixin for defining grid classes"
- "React onhover event" https://stackoverflow.com/questions/32125708/how-can-i-access-a-hover-state-in-reactjs
- "react-js-onclick-event-returning-all-null-values" - use persist() https://stackoverflow.com/questions/26317985/react-js-onclick-event-returning-all-null-values
- React-JS get key index of clicked item - "https://stackoverflow.com/questions/40044861/get-key-index-on-click-es6-react"  - use `data-*`
- "Transparent Z-Index" - image `data-id` would not work
- "React Add inline styles" - to modify CSS-background instead of having an image, or CSS-grid properties
- "Setting Background Image URL in React" - https://stackoverflow.com/questions/39195687/setting-a-backgroundimage-with-react-inline-styles

Time spent

- 1 hr - Initializing React / Scaffolding. Finding transparent image online to add into Airtable
- 1 hr - Compressing and resizing image assets using imagemagick
- 1 hr - Writing ths first pull request #1 to connect backend to frontend, and populate images
- 1 hr - Replicating starting css grid system
- 1 hr - css grid

Compression methods

```
mogrify -path output/ -resize 300 *.jpg
```