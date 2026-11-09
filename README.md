# LiveLines 🎨

Real-time collaborative whiteboard web application built with Next.js, TypeScript, Express, Socket.IO, Tailwind CSS, and HTML5 Canvas.

## ✨ Features
- **Real-Time Collaboration**: Multi-user drawing powered by WebSockets (Socket.IO).
- **Rooms**: Create private rooms with custom 4-character room codes or share direct links.
- **Drawing Tools**: Freehand drawing, shapes (rectangles, circles, lines), eraser, stroke size, and color picker.
- **Canvas Controls**: Background color picker, image upload to canvas, undo/redo history, and canvas minimap.
- **In-Room Chat**: Real-time room chat with participants.
- **Live User Tracking**: Cursor tracking showing other users' mouse movements and usernames.

## 🛠️ Tech Stack
- **Frontend**: Next.js 12, React 17, Tailwind CSS, Recoil, Framer Motion
- **Backend**: Node.js, Express, Socket.IO
- **Language**: TypeScript

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or v18 recommended)
- npm or yarn

### Installation
1. Clone or download the repository:
   ```bash
   cd LiveLines
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Running Locally
Run the development server:
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production
```bash
npm run build
npm start
