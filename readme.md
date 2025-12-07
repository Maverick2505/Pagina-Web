# 🌐 My 3D Web Portfolio

Welcome to my personal web portfolio!  
Here I showcase my 3D designs created in **Blender** and exported as **.glb** files.  
The website allows users to preview each model interactively using **<model-viewer>**, and includes a profile section along with a menu to choose which design to view.

---

## 👤 About Me

**Héctor González Pacheco Illescas**  
I am a 5th-semester student of the **Computer Systems Engineering** program.  
I enjoy working with Blender, 3D modeling, and learning web development.

📩 Email: **hector.gpillescas@gmail.com**  
🐱 GitHub: **https://github.com/Maverick2505**  
🌐 Live Page: **https://maverick2505.github.io/Pagina-Web/**

---

## 🖥️ Technologies Used

- **HTML5**  
- **CSS3**  
- **JavaScript**  
- **Model Viewer** (Google Web Components)  
- **GitHub Pages** (for hosting the website)

---

## 📁 Project Structure

/ (root folder)
│── index.html
│── modelo.html
│── perfil.html
│── styles/
│ └── style.css
│── models/
│ └── setup_gamer_graficacion.glb
│ └── toad.glb
│ └── ballena.glb
└── img/
└── foto.jpg
└── ballena.png
└── setup_gamer.png
└── toad.png


---

## 🎨 Website Features

✔ Interactive 3D model viewer  
✔ Menu to switch between different Blender designs  
✔ Personal profile section  
✔ Responsive design for desktop and mobile  
✔ Clean folder structure (models, images, styles)

---

## 🔧 How to Add a New 3D Model

1. Export your Blender design as a **GLB file** (with embedded textures).  
2. Place the `.glb` file inside the **models/** folder.  
3. Duplicate an existing model HTML page (for example `modelo1.html`).  
4. Replace the viewer source with your new file:

```html
<model-viewer src="models/NEW_MODEL.glb"></model-viewer>
```
5. Add a link to the new model inside index.html.

---

##🚀 Deployment

This website is hosted using GitHub Pages.
Every time you update your code, simply commit and push your changes to the main branch.
GitHub Pages will refresh the website automatically within a few seconds.
