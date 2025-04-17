# My Xebia Data Career in Weeks

👋 Hi, I'm [Lasse](https://github.com/lassebenni/). This is an interactive map of my Xebia Data consulting career, where each week I’ve consulted is a little box. The box's border color represents where I was living/working, the fill color what project/activity I was doing. Tap a box to see more details about that week.

This visualization covers my journey since starting in October 2021 up to today (17-04-2025).

-   [My Linkedin](https://www.linkedin.com/in/lasse-benninga-a462b194/)
-   [📖 Order our book: The Fundamentals of Analytics Engineering](https://www.amazon.com/Fundamentals-Analytics-Engineering-end-end/dp/1837636451)

This project was inspired by [Gina Trapani](https://ginatrapani.org/)'s implementation of [Wait But Why's "Your Life in Weeks"](https://waitbutwhy.com/2014/05/life-weeks.html). Her original code can be found in the [life-in-weeks github repository](https://github.com/ginatrapani/life-in-weeks).

This version is statically-rendered using [Hugo](https://gohugo.io/) and hosted on Netlify.

## 🚀 Setup

1.  Install Hugo:
    ```sh
    brew install hugo  # Mac
    # Or follow instructions at https://gohugo.io/installation/
    ```
2.  Clone this repository and run locally:
    ```sh
    git clone https://github.com/lassebenni/life-in-weeks.git
    cd life-in-weeks
    hugo server -D
    ```
3.  Visit [http://localhost:1313/](http://localhost:1313/).

## ✨ Customize

The site structure follows standard Hugo conventions:

-   `content/index.md` → Main page content and configuration (start date, end year).
-   `data/` → Data files driving the visualization:
    -   `events.yml`: Defines the events, projects, and activities for specific dates.
    -   `colors.yml`: Maps event types/associations to specific fill/border colors.
    -   `tech_categories.yml`: (Likely) Categorizes technologies.
    -   `tech_icons.yml`: Maps technology names to icons.
-   `layouts/` → Hugo templates controlling the HTML structure.
-   `assets/sass/` → SCSS files for styling.
-   `static/` → Static assets (CSS, JS, images, fonts).
-   `hugo.toml` → Main Hugo site configuration.

## Colophon

This page uses [Bootstrap](https://getbootstrap.com/) for layout and interaction, and a smidge of [jQuery](https://jquery.com/) to reflect the current week on the map.

The font is [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display). Colors chosen via [Color Hunt](https://colorhunt.co/). Edited in [Zed](https://zed.dev).
