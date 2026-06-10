# EduConnect - Educational Website

A fully functional, responsive educational website built with React, HTML, and CSS. EduConnect is a platform designed to showcase online courses, display mentor profiles, and allow users to register for programs.

## 🎯 Project Overview

EduConnect is a multi-page educational platform that includes:
- **Home Page** - Hero section with call-to-action
- **Courses Page** - Browse and filter online courses
- **Mentors Page** - View mentor profiles and expertise
- **Register Page** - User registration form for programs
- **About Page** - Information about EduConnect
- **Contact Page** - Get in touch with the team

## ✨ Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ React component-based architecture
- ✅ Clean and modern UI with CSS
- ✅ Course filtering and search functionality
- ✅ Mentor profiles with expertise areas
- ✅ User registration form with validation
- ✅ Mock API data for courses and mentors
- ✅ Navigation between pages with React Router
- ✅ Professional layout and styling

## 🛠️ Tech Stack

- **Frontend Framework:** React 18
- **Styling:** CSS3 (Responsive Design)
- **Routing:** React Router v6
- **Build Tool:** Create React App
- **Package Manager:** npm/yarn

## 📦 Project Structure

```
web/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── CourseCard.jsx
│   │   ├── MentorCard.jsx
│   │   ├── Footer.jsx
│   │   └── ...
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Courses.jsx
│   │   ├── Mentors.jsx
│   │   ├── Register.jsx
│   │   ├── About.jsx
│   │   └── Contact.jsx
│   ├── data/
│   │   ├── courses.json
│   │   └── mentors.json
│   ├── styles/
│   │   ├── index.css
│   │   ├── navbar.css
│   │   ├── hero.css
│   │   ├── courses.css
│   │   ├── mentors.css
│   │   └── ...
│   ├── App.jsx
│   ├── index.jsx
│   └── index.html
├── package.json
└── .gitignore
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/hansinitadaveni28-28/web.git
cd web
```

2. **Install dependencies:**
```bash
npm install
```

3. **Start the development server:**
```bash
npm start
```

4. **Open your browser:**
Navigate to `http://localhost:3000`

## 📄 Available Pages

| Page | Path | Description |
|------|------|-------------|
| Home | `/` | Landing page with hero section and featured courses |
| Courses | `/courses` | Browse all available courses with filters |
| Mentors | `/mentors` | View mentor profiles and their expertise |
| Register | `/register` | Sign up for programs |
| About | `/about` | Learn about EduConnect |
| Contact | `/contact` | Contact form and information |

## 🎨 Design Features

- **Responsive Breakpoints:** Mobile (320px), Tablet (768px), Desktop (1024px+)
- **Color Scheme:** Professional blue and modern gradients
- **Typography:** Clear hierarchy with readable fonts
- **Interactive Elements:** Hover effects, smooth transitions
- **Accessibility:** Semantic HTML, proper contrast ratios

## 📋 Components

### Navbar
Navigation component with links to all pages and responsive mobile menu

### Hero Section
Eye-catching banner with call-to-action button

### Course Card
Reusable component displaying course information with image, title, description, and price

### Mentor Card
Profile component showing mentor details, expertise, and bio

### Footer
Site-wide footer with links and contact information

## 🔄 Data Structure

### Course Object
```json
{
  "id": 1,
  "title": "Web Development Fundamentals",
  "description": "Learn the basics of HTML, CSS, and JavaScript",
  "price": "$49.99",
  "duration": "8 weeks",
  "level": "Beginner",
  "category": "Web Development",
  "image": "image-url"
}
```

### Mentor Object
```json
{
  "id": 1,
  "name": "John Doe",
  "title": "Full Stack Developer",
  "bio": "Expert in web development with 10+ years experience",
  "expertise": ["React", "Node.js", "MongoDB"],
  "image": "image-url"
}
```

## 📝 Forms

### Registration Form
- Name, Email, Phone
- Program Selection
- Experience Level
- Terms & Conditions acceptance

### Contact Form
- Name, Email, Subject
- Message
- Form validation

## 🔒 Validation

- Email format validation
- Required field validation
- Phone number format validation
- Password strength check (for registration)

## 🌐 Responsive Design

The website is fully responsive with:
- Mobile-first approach
- CSS Flexbox and Grid layouts
- Media queries for all screen sizes
- Touch-friendly buttons and navigation

## 📦 Dependencies

```json
{
  "react": "^18.0.0",
  "react-dom": "^18.0.0",
  "react-router-dom": "^6.0.0"
}
```

## 🚀 Deployment

To build for production:

```bash
npm run build
```

This creates an optimized production build in the `build/` directory.

### Deploy to GitHub Pages
```bash
npm run deploy
```

Or deploy to:
- Vercel
- Netlify
- Heroku
- AWS Amplify

## 📚 Learning Resources

- [React Documentation](https://react.dev)
- [React Router Documentation](https://reactrouter.com)
- [MDN CSS Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Web Accessibility](https://www.w3.org/WAI/)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💼 Author

**Your Name** - EduConnect Developer

---

## 📞 Support

For support, email support@learnflu.com or open an issue on GitHub.

## 🎓 Course Categories

- Web Development
- Mobile Development
- Data Science
- UI/UX Design
- Cloud Computing
- Machine Learning
- DevOps

---

**Last Updated:** June 2026
**Version:** 1.0.0

