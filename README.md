# Reid & Megan's Wedding Website

This repository contains the source code for **Reid & Megan’s Wedding Website**, built using the [Dimension template](https://html5up.net/dimension) by HTML5 UP. It is a single-page responsive wedding site with sections for details, RSVP, registry, gallery, and more.

## 📖 Features

- **Responsive Design** – Mobile-friendly layout powered by HTML5 UP’s Dimension theme.
- **Countdown Timer** – Displays days and hours until the wedding date.
- **Interactive Sections**:
  - **Details** – Ceremony, reception, and hotel block information.
  - **Our Story** – Background on Reid & Megan’s journey together.
  - **Wedding Party** – Bridal and groom’s party members.
  - **RSVP** – Integrated with Google Forms for guest responses.
  - **Registry** – Links to Target and other registries.
  - **Gallery** – Image grid with lightbox popups.
  - **Things To Do** – Local attractions and activities in Johnson City, TN.
  - **FAQ** – Common questions answered (dress code, parking, kids policy, etc.).

## 🛠️ Technologies Used

- **HTML5 / CSS3** – Core layout and styles.
- **JavaScript** – Countdown timer, RSVP handling, and smooth gallery close.
- **jQuery** – Required by HTML5 UP’s Dimension template.
- **Google Maps Embed** – Venue map integration.
- **Google Forms** – RSVP submission backend.

## 📂 Project Structure

```
├── index.html        # Main wedding website page
├── assets/
│   ├── css/
│   │   ├── main.css
│   │   └── noscript.css
│   ├── js/
│   │   ├── jquery.min.js
│   │   ├── browser.min.js
│   │   ├── breakpoints.min.js
│   │   ├── util.js
│   │   └── main.js
├── images/           # Gallery and section images
└── README.md         # Documentation
```

## 🚀 Deployment

1. Clone or download the repository.
2. Place it on a static hosting service such as:
   - [Netlify](https://www.netlify.com/)
   - [GitHub Pages](https://pages.github.com/)
   - [Vercel](https://vercel.com/)
3. Ensure all `assets/` and `images/` folders are uploaded alongside `index.html`.

## ✏️ Customization

- **Wedding Details** – Update ceremony time, location, and hotel info inside `index.html` under the `#details` section.
- **Hotel Blocks** – Replace the Marriott / Holiday Inn details and booking links with your own.
- **Our Story** – Replace text and images in the `#story` section.
- **Wedding Party** – Fill in names in the `#party` section.
- **RSVP** – Replace the Google Form `action` URL with your own form’s endpoint.
- **Registry** – Add or remove registry links in the `#registry` section.
- **Gallery** – Add images to `/images` and update `<a href="#gimgXX">` and `<img src="...">` tags in the `#gallery` section.
- **Things To Do** – Swap in or expand the local attractions list.
- **FAQ** – Edit answers or add new questions under the `#faq` section.

## 📝 License

This project is based on the [Dimension template by HTML5 UP](https://html5up.net/dimension), released under the [Creative Commons Attribution 3.0 License](https://html5up.net/license).

You are free to use, modify, and host this site for personal and commercial purposes with proper attribution.

---

💍 **Created with love for Reid & Megan’s wedding – December 20, 2025.**
