# weather-world

> 🌐 **Live Project Website:** [https://weather-world-io.netlify.app/](**https://weather-world-io.netlify.app/**)

## Whether Weather 🌦️
<p align="center"> 
   <img src="./assets/logo.png" alt="Whether Weather Logo" height="140"> 
</p> 

### 📌 Project Description

**Whether Weather** simulates a global weather information for multiple cities, including current conditions, seven-day forecast, alongside a dashboard overview, user preferences interface, and an additional wind chill calculator feature. 
All weather data used in this project is hardcoded. This multi-page weather forecasting website was built using **Eleventy (11ty)**, **Nunjucks**, **Bulma**, **HTML**, and **CSS**. 

## Getting Started

### ⚙️ Installation & Running the Project

Follow the steps below to run the project locally. 

1.	Ensure **Node.js, npm, Git** are installed on your machine. 
You can verify the setup by running in a command prompt terminal (cmd).

```
node -v
npm -v
git –version
```

2.	Download or clone the repository.
   
Clone the project from **GitHub** and move into the project directory:

```
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### Sources

- [Downloading files from GitHub](https://docs.github.com/en/get-started/start-your-journey/downloading-files-from-github)
- [Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)


3.	Install dependencies using npm:
   
   `npm install`

   This will install **Eleventy** and all other dependencies defined in `package.json`.

4.	Start **Eleventy**’s development server:
   
Run `npx @11ty/eleventy --serve`  

**Eleventy** will build the site, monitor file changes and serve the project locally during development.

5.	Open your browser and visit:
   
`http://localhost:8080`

6.	Deploy the project from **Github** on **Netlify** (optional)

### Sources

- [A Step-by-Step Guide to Deploying on Netlify](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/)


### 🚀 Usage

Once the project is running, users can:

* Browse the **Dashboard** to quickly compare weather in different cities
* Click a city card to open a **City Focus Page** with detailed weather information
* Use the **Settings Page** to select favourite cities and preferred weather conditions (UI only)
* Explore the **Wind Chill Calculator** to understand how wind speed affects perceived temperature
  
Navigation is available on every page using the main menu.

### 🔧 Configuration

City and weather data are stored in a global JSON file:

`/_data/cities.json`

To add or modify cities:

* Edit `cities.json`

Eleventy will automatically update the dashboard, city pages, and settings options.

### 🗂 Project Structure

```
_includes/
  layouts/
    base.njk

  partials/
    footer.njk
    nav.njk

  components/
    dashboard-card.njk
    day-summary.njk
    toggle.njk

_data/
  cities.json

pages/
  index.njk
  dashboard.njk
  city.njk
  settings.njk
  wind-chill-calculator.njk

_css/
  styles.css
```

### 🧰 Tech Stack & Tools

<p align="center">
  <img src="assets/logos/eleventy-logo.png" alt="Eleventy" height="100"/>
  <img src="assets/logos/nunjucks-logo.png" alt="Nunjucks" height="100"/>
  <img src="assets/logos/bulma-logo.png" alt="Bulma" height="100"/>
  <img src="assets/logos/html5-logo.png" alt="HTML5" height="100"/>
  <img src="assets/logos/css-logo.png" alt="CSS3" height="100"/>
  <img src="assets/logos/netlify-logo.png" alt="Netlify" height="100"/>
  <img src="assets/logos/github-logo.png" alt="GitHub" height="100"/>
</p>

**Eleventy (11ty)** – Static site generator

**Nunjucks** – Templating engine

**Bulma** – CSS framework for layout and styling

**HTML5 / CSS3** – Markup and styling

**Netlify** – Deployment platform

**GitHub** – Version control and repository hosting

### 📚 Documentation

**Eleventy**: https://www.11ty.dev/docs/

**Nunjucks**: https://mozilla.github.io/nunjucks/

**Bulma**: https://bulma.io/documentation/

**HTML**: https://developer.mozilla.org/en-US/docs/Web/HTML

**CSS**: https://developer.mozilla.org/en-US/docs/Web/CSS

**Netlify**: https://docs.netlify.com/

**GitHub**: https://docs.github.com/en

### 🤝 Contributing Guidelines

This project was created for an academic assignment. Contributions are not expected, but suggestions and feedback are welcome.

### 📄 License

This project was completed for educational purposes as part of a web development course.

### 📬 Contact Information

For questions related to this project, please contact the author [Boun Chun](https://github.com/bounchun) or the course instructor [John Reillis](https://github.com/johnrellis).












