# Restaurant Link Tree for Restaurant

This project is a responsive link tree webpage designed for a restaurant. It features a clean and modern design with social media icons and navigation links. The page is fully responsive and adapts to different screen sizes, including mobile devices.

## Features

- **Responsive Design**: The page adjusts seamlessly for devices with a width of 600px or less.
- **Social Media Integration**: Includes icons for WhatsApp, TikTok, and Snapchat.
- **Navigation Links**: Provides links to the restaurant's menu, locations, and about page.
- **Customizable**: Easy to update links, icons, and styles.

## Technologies Used

- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling and responsiveness.

## How to Use

1. Clone or download the repository.
2. Open the `index.html` file in your browser to view the page.
3. Customize the links and icons in the `index.html` file as needed.
4. Modify the styles in the `style.css` file to match your branding.

## Responsive Design

The page includes a media query for devices with a maximum width of 600px. This ensures the layout is optimized for smaller screens, such as smartphones.

```css
@media (max-width: 600px) {
  .container {
    width: 90%;
    padding: 15px;
  }

  .logo .circle {
    width: 60px;
    height: 60px;
    line-height: 60px;
    font-size: 1.5rem;
  }

  .social-icons img {
    width: 25px;
    height: 25px;
  }

  .links .link {
    font-size: 0.9rem;
    padding: 8px;
  }
}
```
