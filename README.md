# LinkTree Static Page: HTML & CSS Only

This project is a simple static LinkTree-like page built entirely with HTML and CSS. It allows users to list multiple links in one place, making it easier to share multiple resources using a single URL. 

## Features

- **Minimalistic Design**: A clean and responsive design ensures that the page looks good on all devices.
- **No Javascript**: This project only uses HTML and CSS, which ensures fast loading times and increased compatibility across browsers.
- **Customizable**: Easily change colors, fonts, and layout to make it fit your brand.

## How to Use

### 1. Clone the Repository

First, you'll need to clone this repository to your local machine:

```bash
git clone https://github.com/eaitae/eaitae.github.io
```

### 2. Navigate to the Project Directory

```bash eaitae.github.io
cd 
```

### 3. Edit the HTML

#### a) Update Links

Open the `index.html` file in your favorite text editor. Look for the section where the links are defined and modify them as per your needs.

Example:

```html
<div class="link-item">
  <a href="YOUR_LINK_HERE" target="_blank">Your Link Text Here</a>
</div>
```

Replace `YOUR_LINK_HERE` with your desired URL and `Your Link Text Here` with your desired text.

#### b) Update Favicon

To change the favicon, replace the `favicon.png` file in your project directory with your new favicon image. Make sure to keep the name as `favicon.png` or if you change the name, update it in the HTML as well:

```html
<link rel="icon" href="YOUR_FAVICON_FILENAME.png" />
```

#### c) Update Title

To change the title that appears on the browser tab, modify the content between the `<title>` tags:

```html
<title>YOUR_TITLE_HERE</title>
```

Replace `YOUR_TITLE_HERE` with your desired title.

#### d) Update Header Banner

To change the header banner, replace the `Banner.png` file in your project directory with your new banner image. Ensure the image dimensions are appropriate for a header banner. 

Update the HTML code if you change the filename:

```html
<img
  class="banner"
  src="YOUR_BANNER_FILENAME.png"
  alt="YOUR_ALT_TEXT_DESCRIPTION_HERE"
/>
```

Replace `YOUR_BANNER_FILENAME.png` with your new banner's filename and `YOUR_ALT_TEXT_DESCRIPTION_HERE` with a brief description of the image for accessibility purposes.

---

### 4. Customize Styles (Optional)

If you wish to change the look of your page, you can easily edit the `styles.css` file. Here you can adjust colors, fonts, and other styles to better fit your brand.

### 5. Deploy

Once you're done making changes, you can deploy your page to your favorite hosting provider or use static site hosts like GitHub Pages, Vercel, or Netlify.

## License

This project is open source and available under the [MIT License](LICENSE).
