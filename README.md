# The Office of Zak Farnworth

A personal website inspired by the [GOV.UK Design System](https://design-system.service.gov.uk), featuring a clean, accessible, and professional design with a welcome section, about page, blog, and press centre.

## Structure

- **Home** – Hero welcome with photo, about preview, latest blog posts, and press highlights
- **About** – Full biography and background
- **Blog** – 6 sample posts with individual article pages
- **Press Centre** – Press releases and news items with dedicated pages

## Adding Your Photo

1. Add a portrait photo named `zak.jpg` to the `images/` folder
2. Recommended size: 500×650 pixels (portrait orientation)
3. If no image is found, a placeholder will be displayed automatically

## Running Locally

Open `index.html` in a browser, or use a simple local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000`

## Customisation

- **Content**: Edit the HTML files to update text, add posts, or modify press releases
- **Styles**: Modify `css/styles.css` for colours, fonts, and layout
- **Colour palette**: CSS variables in `:root` define navy, gold, cream, and burgundy

## Credits

Design inspired by the official website of the Royal Family. Built with plain HTML, CSS, and JavaScript—no frameworks required.
