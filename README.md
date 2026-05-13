# 📚 My Digital Library

An interactive web application designed to explore, search, and filter a collection of books. This project focuses on clean JavaScript logic and modern CSS layout techniques to create a seamless user experience.

## View it live 
**Github:** [https://lofstromfelicia.github.io/technigo-project-library/]

**Cloudflare Pages:** [the-grand-digital-library-project-technigo.pages.dev]

## 🚀 Key Features
- **Masonry Layout:** Achieved using `column-width` to create an organic, library-like feel where book cards of different heights fit together perfectly. 
- **Dynamic Rendering:** Books are rendered dynamically from a JavaScript object array.
- **Genre Filtering:** Easily sort through the collection by genres like Fantasy, Science Fiction, Mystery, and more.
- **Live Search:** A real-time search bar that filters by book title or author as you type.
- **Advanced Sorting:** Organize the library by rating, publication year, or alphabetically.
- **Dark Mode:** A seamless transition between light and dark themes, featuring a custom-designed floating toggle. 
- **Surprise Me Mode:** A randomizer function that picks a single book - perfect for the indecisive reader! 

## 🛠 Technical Highlights

### Logic-Driven UI 
Instead of static HTML, the entire library is built on a "single source of truth" (a Javascript array). This allows for complex filtering and sorting without ever needing to reload the page. 

### Responsive Architecture
**Mobile-First Approach:** The control panel and search bar are designed for thumb-friendly mobile use first, then expand into a sophisticated layout for tablet and desktop. 
**Dynamic Masonry:** The layout automatically calculates the optimal number of columns based on available space, ensuring a fluid experience on all screen sizes.

### Robust JavaScript Implementation
- **Array Methods:** Extensive use of `.filter()`, `.sort()`, and `.forEach()` for efficient data handling.
- **Event Management:** Simultaneous handling of search inputs and filter buttons without logic conflicts.
- **DOM Manipulation:** Optimized innerHTML updates to ensure smooth transitions when the library changes.

---
*Created as part of a web development course, focusing on the synergy between logic and design.*