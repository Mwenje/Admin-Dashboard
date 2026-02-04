# Admin-Dashboard

# 🚀 Admin Dashboard Project

A high-fidelity dashboard layout built as part of my web development journey. This project focuses on mastering **CSS Grid** for complex, nested layouts and responsive design principles.

## 🛠 Features

- **Fully Responsive Sidebar:** A persistent navigation menu with grouped links.
- **Dynamic Project Grid:** A card-based layout that uses `auto-fit` to adjust to screen sizes.
- **Nested Grid Structure:** Uses a "Grid within a Grid" approach to organize the header and main content areas.
- **Clean UI:** Modeled after modern dashboard aesthetics with subtle shadows and clear typography.

## 💡 Lessons Learned

The primary goal of this project was to move beyond basic layouts and tackle a real-world UI challenge. Key takeaways include:

- **Grid Areas are Magic:** Using `grid-template-areas` made the high-level skeleton of the page incredibly easy to manage and visualize.
- **Nesting Logic:** Learning when to use **Grid** (for the macro layout) vs. **Flexbox** (for micro-alignments like icons and buttons).
- **The Power of `minmax()`:** Implementing `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))` allowed the project cards to wrap naturally without a dozen media queries

## 🖥️ Technologies Used

- **HTML5** for semantic structure.
- **CSS3** (Custom Properties, Grid, Flexbox).
- **Google Fonts** (Roboto).
- **Material Design Icons** (via SVG).

## 🚀 How to Run

1.  Clone this repository:

    Bash

    ```
    git clone https://github.com/Mwenje/Admin-Dashboard.git
    ```

2.  Open `index.html` in your favorite browser.
3.  (Optional) View the live demo on **GitHub Pages** [Link your URL here].
