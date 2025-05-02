# 👨‍💻 Personal Portfolio Website

<div align="center">
  
![GitHub stars](https://img.shields.io/github/stars/username/portfolio-website?style=social)
![GitHub forks](https://img.shields.io/github/forks/username/portfolio-website?style=social)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

</div>

<p align="center">
  <img src="./images/logo.png" alt="Portfolio Logo" width="400"/>
</p>

## 📋 Overview

A clean, modern, and interactive personal portfolio website showcasing my web development journey and skills. This single-page application presents a professional profile with smooth navigation and interactive elements.

## ✨ Live Demo

[View Live Demo](#) <!-- Add your deployed site URL here -->

<p align="center">
  <img src="./images/hero.png" alt="Website Preview" width="800"/>
</p>

## 🎯 Features

- **Responsive Design** - Looks great on all devices
- **Interactive Journey Cards** - Color-changing background effects on click
- **Clean Navigation** - Smooth scrolling to different sections
- **Professional Layout** - Modern UI with focused content sections
- **Contact Integration** - Direct email functionality

## 🛠️ Built With

<div align="center">
  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

## 🧩 Project Structure

```
portfolio-website/
│
├── index.html         # Main HTML document
├── main.css           # Style definitions
├── script.js          # Interactive functionality
│
└── images/            # Image assets directory
    ├── logo.png       # Website logo
    ├── hero.png       # Hero section background
    ├── intro-to-web.png
    ├── react.png
    └── backend.png
```

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/username/portfolio-website.git
   ```

2. Navigate to project directory
   ```bash
   cd portfolio-website
   ```

3. Open `index.html` in your browser
   ```bash
   # On Mac
   open index.html
   
   # On Windows
   start index.html
   
   # On Linux
   xdg-open index.html
   ```

## 📱 Responsive Design

The website is fully responsive and adapts to:
- Desktop screens
- Tablets
- Mobile devices

## 🔍 Code Highlights

### Interactive Background Change
```javascript
function changeBackgroundColor(color){
    let section = document.getElementById('coding-journey');
    section.style.backgroundColor = color;
}

document.getElementById('intro').addEventListener('click', 
    () => changeBackgroundColor("#2CA02C"));
```

### Clean CSS Reset
```css
*,
*::before,
*::after {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  border: none;
  max-width: 100%;
}
```

## 🔄 Future Improvements

- [ ] Add dark/light mode toggle
- [ ] Include project gallery section
- [ ] Implement form validation for contact form
- [ ] Add animations for smoother transitions
- [ ] Include testimonials section

## 👤 About Me

Hi! I'm Jospin Nabonyimana, a passionate web developer focused on creating beautiful and functional web experiences.

- 💻 Front-end & back-end development
- ⚙️ HTML, CSS, JavaScript, and React
- 🚀 Continuous learner and builder

## 📬 Contact

- **Email:** [jospinnabonyimana@gmail.com](mailto:jospinnabonyimana@gmail.com)
- **GitHub:** nabonyimanajospin(https://github.com/nabonyimanajospin)
- **LinkedIn:** https://www.linkedin.com/in/jospin-nabonyimana-88497232a/ <!-- Add your LinkedIn profile URL -->

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p>Made with ❤️ by Jospin Nabonyimana</p>
</div>
