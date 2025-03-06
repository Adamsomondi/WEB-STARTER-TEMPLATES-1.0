# WEB-STARTER-TEMPLATES
A collection of ready-to-use templates for every modern web development stack. Whether you're building with Tailwind CSS, Bootstrap,Material design,React,Nextjs,Gatsby,Angular,Vue Node.js, Django,flask Express.js,laravel get started quickly with pre-configured setups.
# Bootstrap-simple-Template

<p>A minimal Bootstrap setup using npm and SASS,but without build tools. Perfect for quick learning,prototyping and small projects</p>
  <pre>
  Bootstrap-simple-Template/
├── css/
│   ├── custom.css
│   ├── custom.css.map
│   └── styles.css
├── scss/
│   ├── css/
│   └── custom.scss
├── node_modules/
├── index.html
├── package-lock.json
└── package.json
  </pre>
  
### Install Sass globally
npm install -g sass

<p><b>Clone this repository</b></p>

RUN ON GITBASH
 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES.git

 cd  WEB-STARTER-TEMPLATES/Bootstrap-simple-Template

npm install --save-dev autoprefixer@10.4.20 bootstrap@5.3.3 postcss-cli@11.0.0 postcss@8.4.35 sass@1.63.6

sass --watch ./scss/custom.scss ./css/custom.css
```

# Tailwind-simple-Template

<p>A minimal Tailwind setup using npm, Postcss, autoprefixer, postcss-cli but without build tools. Perfect for quick learning,prototyping and small projects</p>
 <pre>
tailwind-simple-Template/
├── dist/
│   └── styles.css
├── node_modules/
├── src/
│   └── styles.css
|---index.html
├── package.json
├── postcss.config.js
└── tailwind.config.js
  </pre>
  
<p><b>Clone this repository</b></p>

RUN ON GITBASH

 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES.git

cd  WEB-STARTER-TEMPLATES/Tailwind-simple-Template

npm install -D autoprefixer@10.4.20 postcss-cli@11.0.0 postcss@8.5.3 tailwindcss@2.2.19

npm run build
npm run watch
```
