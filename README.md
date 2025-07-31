# Vue Filters 🎨
<img width="1050" height="768" alt="Copy of chatbot" src="https://github.com/user-attachments/assets/5a04f41e-9e4f-4929-b05f-c3e948a1bd40" />

Vue Filters is a modern web-based image editing application built with Vue.js. It brings the power of Photoshop-like filters directly to the browser. With a fast, responsive interface and performance-optimized rendering using WebAssembly and the Canvas API, Vue Filters is a perfect addition to any developer's portfolio.

## 🖼️ Live Demo

> [Click here to view the live demo](https://your-live-link.com)

---

## 📌 Features

- 🌈 Apply stunning visual effects to your images (grayscale, sepia, brightness, contrast, etc.)
- 🧠 Built with best practices in **Vue 3 Composition API**
- 🖼️ Real-time canvas manipulation using the **HTML5 Canvas API**
- ⚡️ Ultra-fast processing with **WebAssembly (WASM)** powered filters
- 🛠 Custom composables for reusable, reactive logic
- 🧪 Type-safe development using **TypeScript**
- 🚀 Lightning-fast builds with **Vite**

---

## ⚙️ Tech Stack

| Technology     | Purpose                                |
|----------------|----------------------------------------|
| Vue 3          | Frontend framework                     |
| Vite           | Build tool for fast HMR and bundling   |
| TypeScript     | Type safety                            |
| WebAssembly    | High-performance filter processing     |
| HTML5 Canvas   | Image rendering and manipulation       |
| Tailwind CSS (optional) | Utility-first CSS styling     |

---

## 🛠 Installation

To get started with the project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/vue-filters.git

# Navigate into the project directory
cd vue-filters

# Install dependencies
npm install

# Run the development server
npm run dev
Open your browser and visit http://localhost:5173 to see the app in action.

📁 Project Structure
graphql
Copy
Edit
vue-filters/
│
├── public/                # Static assets
├── src/
│   ├── assets/            # Image assets and styles
│   ├── composables/       # Custom composables (e.g. useFilter.ts)
│   ├── filters/           # WebAssembly filters and logic
│   ├── components/        # Vue components (ImageUploader.vue, FilterControls.vue, etc.)
│   ├── App.vue            # Root component
│   ├── main.ts            # App entry point
│
├── index.html
├── vite.config.ts
├── package.json
└── README.md
🧠 How It Works
This app allows users to upload an image, apply multiple filters dynamically, and preview the results in real-time. The filter logic is encapsulated using composables and modularized for flexibility. WebAssembly is used for performance-heavy operations like convolution-based filters, giving the app near-native execution speed.

📸 Screenshots
Coming soon: Replace with actual demo screenshots.

🧪 Future Improvements
Export edited images

Undo/redo stack

Add more complex filters (blur, edge detection)

Drag-and-drop UI

Touch support for mobile

🤝 Contributing
Contributions are welcome! If you'd like to improve this app, please fork the repository and submit a pull request.
