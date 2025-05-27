# FurniStudio - 3D Furniture Visualization Platform

A powerful web-based furniture visualization application that allows interior designers to create, visualize, and manage room designs in both 2D and 3D. Perfect for professional interior designers to showcase realistic furniture layouts to clients.

## 🌟 Features

- **Interactive 2D Editor**: Drag-and-drop furniture placement using Konva.js canvas
- **Immersive 3D Viewer**: Realistic 3D visualization with Three.js
- **Room Customization**: Configure room dimensions, colors, and lighting
- **Furniture Library**: Choose from a wide range of furniture models
- **Design Management**: Save, load, and edit multiple designs
- **Authentication**: Secure user accounts with JWT
- **Responsive Design**: Works on desktops, tablets, and mobile devices

## 🚀 Technologies

### Frontend
- **React.js** - UI framework
- **Three.js** - 3D graphics rendering
- **React Three Fiber** - React renderer for Three.js
- **Konva.js** - 2D canvas graphics
- **React Router** - Navigation and routing
- **Tailwind CSS** - Styling and UI components

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web server framework
- **Prisma** - Database ORM
- **SQLite** - Database (development)
- **JWT** - Authentication

## 📋 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/FurniStudio.git
   cd FurniStudio
   ```

2. Set up the backend
   ```bash
   cd server
   npm install
   npx prisma migrate dev
   npm run dev
   ```

3. Set up the frontend
   ```bash
   cd client
   npm install
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## 💻 Usage

1. **Register/Login** to access the platform
2. **Create a new design** from the home page
3. **Configure your room** by setting dimensions and colors
4. **Add furniture** from the catalog
5. **Customize** furniture positions, rotation, and colors
6. **Switch to 3D view** to see a realistic rendering
7. **Save your design** to access it later

## 🔄 Workflow

1. **2D Editor Mode**
   - Set room dimensions and colors
   - Drag and drop furniture
   - Resize and rotate items
   - Configure furniture colors

2. **3D Viewer Mode**
   - View realistic 3D rendering
   - Orbit, pan, and zoom camera
   - Adjust lighting and shadows
   - Save screenshots

## 🧩 Project Structure

```
.
├── client/               # Frontend code
│   ├── public/           # Static assets
│   └── src/
│       ├── assets/       # Images and resources
│       ├── components/   # React components
│       ├── constants/    # App constants and data
│       ├── context/      # React context providers
│       └── pages/        # Main page components
│
└── server/               # Backend code
    ├── prisma/           # Database schema
    └── index.js          # Express server
```

## 🛠️ Future Improvements

- Add more furniture models and textures
- Implement room templates
- Add export functionality (PDF, images)
- Enhance lighting effects
- Add collaborative features
- Support for VR/AR viewing

## 📝 License

MIT License

## 👥 Contributors

For any inquiries or feedback, reach out to me at [Lahiru Senavirathna](https://bit.ly/Lahiru_Senavirathna).

---

*FurniStudio - Transform your space with professional furniture visualization* 
