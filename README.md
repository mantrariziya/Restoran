# Restoran

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-3.4.1-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-5.10.0-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![Bootstrap Icons](https://img.shields.io/badge/Bootstrap_Icons-1.4.1-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Owl Carousel](https://img.shields.io/badge/Owl_Carousel-2.3.4-E44D26?style=for-the-badge&logoColor=white)
![WOW.js](https://img.shields.io/badge/WOW.js-Animate.css-FF6B6B?style=for-the-badge&logoColor=white)
![Tempus Dominus](https://img.shields.io/badge/Tempus_Dominus-Bootstrap_4-563D7C?style=for-the-badge&logoColor=white)
![Moment.js](https://img.shields.io/badge/Moment.js-222222?style=for-the-badge&logoColor=white)

![Restoran Preview](img/bootstrap-restaurant-template.jpg)

A fully responsive, multi-page restaurant website template built with HTML5, CSS3, Bootstrap 5, and jQuery. Covers everything from food menus to table reservations — ready to customize and deploy.

## Why This Project?

Most small restaurant businesses either have no web presence or rely on outdated, non-responsive sites. This project provides a clean, professional, multi-page restaurant website that can be customized and handed off quickly — covering menus, table booking, team showcase, testimonials, and contact — without requiring any backend or build tooling.

## Features

| Feature | Description |
|---|---|
| Multi-page layout | 8 pages: Home, About, Menu, Service, Booking, Team, Testimonial, Contact |
| Responsive navbar | Sticky on scroll, hover dropdown on desktop, collapse on mobile |
| Page load spinner | Full-screen spinner shown on initial page load |
| Food menu tabs | Breakfast, Lunch, Dinner tabs with item cards and prices |
| Table booking form | Name, email, date/time picker, guest count, special request fields |
| Video modal | YouTube embed with autoplay on open, stops on close |
| Testimonials carousel | Owl Carousel with autoplay, dots, and responsive breakpoints |
| Team section | Chef cards with social links (Facebook, Twitter, Instagram) |
| Animated counters | Years of experience and master chefs count with CounterUp.js |
| WOW.js animations | Scroll-triggered fade, zoom, and slide animations |
| Back to top button | Smooth scroll to top using easing |
| Newsletter form | Email input with signup button in footer |

## Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| HTML5 | — | Page structure |
| CSS3 | — | Styling and layout |
| Bootstrap | 5.0.0 | Responsive grid and components |
| jQuery | 3.4.1 | DOM manipulation and event handling |
| Owl Carousel | — | Testimonials slider |
| WOW.js + Animate.css | — | Scroll-triggered animations |
| Tempus Dominus | Bootstrap 4 build | Date/time picker |
| Moment.js + Moment Timezone | — | Date/time handling for Tempus Dominus |
| CounterUp.js | — | Animated number counters |
| Waypoints.js | — | Scroll position detection |
| Font Awesome | 5.10.0 | Icons |
| Bootstrap Icons | 1.4.1 | Additional icons |
| Google Fonts | — | Heebo, Nunito, Pacifico |

## Project Structure

```
Restoran/
├── css/
│   ├── bootstrap.min.css
│   └── style.css
├── img/
│   ├── hero.png
│   ├── bg-hero.jpg
│   ├── about-1.jpg ... about-4.jpg
│   ├── menu-1.jpg ... menu-8.jpg
│   ├── team-1.jpg ... team-4.jpg
│   ├── testimonial-1.jpg ... testimonial-4.jpg
│   └── video.jpg
├── js/
│   └── main.js
├── lib/
│   ├── animate/
│   ├── counterup/
│   ├── easing/
│   ├── owlcarousel/
│   ├── tempusdominus/
│   ├── waypoints/
│   └── wow/
├── scss/
│   └── bootstrap/
├── index.html
├── about.html
├── menu.html
├── service.html
├── booking.html
├── team.html
├── testimonial.html
├── contact.html
├── .gitignore
├── LICENSE
└── README.md
```

## Pages

| Page | File |
|---|---|
| Home | index.html |
| About | about.html |
| Menu | menu.html |
| Services | service.html |
| Booking | booking.html |
| Team | team.html |
| Testimonial | testimonial.html |
| Contact | contact.html |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/mantrariziya/Restoran.git
   cd Restoran
   ```

2. Open in browser:
   ```bash
   open index.html
   ```

No build step or server required — pure static HTML/CSS/JS.

## Security

- No backend or database — static site only
- No API keys or credentials in source code
- All external resources loaded via CDN (jQuery, Bootstrap, Google Fonts, Font Awesome)
- No user data is collected or stored

## Roadmap

- Add backend for booking form (Node.js or PHP)
- Connect newsletter form to an email service
- Replace placeholder menu items with real content and images
- Implement online ordering system
- Add Google Maps integration on the contact page

## Author

**Mantra Riziya**

[![GitHub](https://img.shields.io/badge/GitHub-mantrariziya-181717?style=flat&logo=github)](https://github.com/mantrariziya)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mantra--riziya-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/mantra-riziya-7aa1752b6)
[![Email](https://img.shields.io/badge/Email-riziyamantra@gmail.com-D14836?style=flat&logo=gmail)](mailto:riziyamantra@gmail.com)

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

