# Modern HTML Boilerplate

An open-source HTML, SCSS, JavaScript and Gulp boilerplate for building modern, production-ready websites.

## ✨ Features

* HTML5 boilerplate
* SCSS/SASS support
* JavaScript ES6+ support
* Gulp-based build system
* LTR and RTL support
* English and Arabic builds
* CSS & JavaScript minification
* Autoprefixer support
* HTML partials with `gulp-file-include`
* Vendor JS bundling
* BrowserSync live reload
* Modern Node.js support

## 📁 Structure

```text
src/
├── assets/
│   ├── css/
│   ├── img/
│   ├── scripts/
│   └── scss/
├── include/
├── index.html
└── ...

build/
├── ar/
├── assets/
└── ...
```

## 🚀 Getting Started

### 1. Clone

```bash
git clone https://github.com/YOUR_USERNAME/modern-html-boilerplate.git
cd modern-html-boilerplate
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start development

```bash
npm run dev
```

### 4. Create production build

```bash
npm run build
```

The compiled files will be generated inside the `build` directory.

## 📦 Output

The production build generates minified assets:

```text
build/assets/css/style.min.css
build/assets/css/style-rtl.min.css
build/assets/js/vendors.min.js
build/assets/js/scripts.min.js
```

## 🌐 LTR & RTL

The boilerplate supports both LTR and RTL layouts.

* English → LTR
* Arabic → RTL

RTL styles are automatically generated from the same SCSS source.

## 🤝 Contributing

Contributions, improvements and suggestions are welcome.

Feel free to fork the project, create a branch, and submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ for the frontend community.
