# Academic Project Page Template

This is a clean, modern website template for academic project pages. It's based on the Nerfies project page design, but with all project-specific content removed, leaving only the theme and structure.

## Features

- **Responsive Design**: Built with Bulma CSS framework
- **Modern UI Components**: 
  - Navigation bar with dropdown menus
  - Hero sections for titles and teasers
  - Carousels for showcasing results
  - Video embeds and media support
  - Interactive sliders
  - Clean typography with Google Fonts
- **Academic-Focused**: Pre-structured sections for abstracts, BibTeX citations, author lists, etc.
- **Easy to Customize**: Simply replace the placeholder content with your own

## Usage

1. Replace placeholder text in `index.html` with your project details:
   - Project title and description
   - Author names and affiliations
   - Links to paper, code, and data
   - Abstract and content sections

2. Add your media files:
   - Place images in `static/images/`
   - Place videos in `static/videos/`

3. Customize the styling if needed:
   - Main styles are in `static/css/index.css`
   - Bulma framework provides the base styling

## File Structure

```
.
├── index.html              # Main HTML file
├── static/
│   ├── css/               # Stylesheets
│   │   ├── bulma.min.css
│   │   ├── bulma-carousel.min.css
│   │   ├── bulma-slider.min.css
│   │   ├── fontawesome.all.min.css
│   │   └── index.css      # Custom styles
│   ├── js/                # JavaScript files
│   │   ├── bulma-carousel.min.js
│   │   ├── bulma-slider.min.js
│   │   ├── fontawesome.all.min.js
│   │   └── index.js
│   └── images/            # Your images go here
│       └── favicon.svg
```

## Credits

This template is based on the [Nerfies project page](https://nerfies.github.io). 

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
