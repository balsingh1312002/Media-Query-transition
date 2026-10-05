# Responsive Boxes – Desktop to Mobile

## 📌 About the Project

This project demonstrates a **responsive webpage layout** using HTML and CSS. It contains three boxes with text content that automatically changes its layout and styling based on the screen size.

The main purpose of this project is to understand **CSS Flexbox, Media Queries, responsive layouts, font sizing, and desktop-to-mobile transitions**.

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox
- Media Queries

## ✨ Features

- Three responsive content boxes
- Horizontal layout on desktop screens
- Vertical layout on mobile screens
- Different styles for different screen sizes
- Responsive font sizes
- Responsive element heights
- Changes font style and font family on smaller screens
- Simple and beginner-friendly responsive design

## 📱 Responsive Breakpoints

| Screen Width | Responsive Changes |
|---|---|
| Above 904px | Three boxes displayed horizontally |
| Below 904px | Font size and box height are adjusted |
| Below 856px | Boxes change to a vertical column layout and italic styling is applied |
| Below 295px | Font size is reduced and font family is changed |
| Below 252px | Font size and box height are further adjusted |

## 💻 Desktop View

On larger screens, the three boxes are arranged horizontally using CSS Flexbox.

```css
body {
    display: flex;
    gap: 10px;
    padding: 10px;
}
