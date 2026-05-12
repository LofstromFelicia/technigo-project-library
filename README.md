# 📚 My Digital Library

An interactive web application designed to explore, search, and filter a collection of books. This project focuses on clean JavaScript logic and modern CSS layout techniques to create a seamless user experience.

## View it live 
Github: https://lofstromfelicia.github.io/technigo-project-library/

Cloudflare Pages: the-grand-digital-library-project-technigo.pages.dev

## 🚀 Key Features

- **Dynamic Rendering:** Books are rendered dynamically from a JavaScript object array.
- **Genre Filtering:** Easily sort through the collection by genres like Fantasy, Science Fiction, Mystery, and more.
- **Live Search:** A real-time search bar that filters by book title or author as you type.
- **Advanced Sorting:** Organize the library by rating, publication year, or alphabetically.
- **"Surprise Me" Mode:** A randomizer function that picks a book for the user—perfect for those who can't decide what to read next.
- **Interactive UI:** Includes custom hover effects and a "like" system for individual book cards.

## 🛠 Technical Highlights

### Intrinsic Design & Fluid Layout
Instead of relying on rigid, breakpoint-heavy media queries, this project utilizes **Intrinsic Design** principles. By using **CSS Grid with `auto-fill` and `minmax()`**, the layout calculates the optimal number of columns based on the available space. 
- No "stuttering" between fixed sizes.
- Content-driven responsiveness that works on any device.

### Robust JavaScript Implementation
- **Array Methods:** Extensive use of `.filter()`, `.sort()`, and `.forEach()` for efficient data handling.
- **Event Management:** Simultaneous handling of search inputs and filter buttons without logic conflicts.
- **DOM Manipulation:** Optimized innerHTML updates to ensure smooth transitions when the library changes.

---
*Created as part of a web development course, focusing on the synergy between logic and design.*