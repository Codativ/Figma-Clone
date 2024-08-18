# Figma Clone

This project is a Figma clone built with Next.js, Liveblocks, and Fabric.js. The aim is to provide a collaborative design tool with real-time editing features, similar to Figma.

## Features

- **Real-Time Collaboration**: Built using Liveblocks, enabling multiple users to work on the same design simultaneously.
- **Canvas Drawing**: Powered by fabricjs, providing a flexible and robust canvas for drawing shapes, images, and text
- **Undo/Redo Functionality**: Supports undo and redo actions for seamless editing.

## Technologies Used

- **Next.js**: The React framework for server-rendered applications.
- **Liveblocks**: Handles real-time collaboration and state synchronization.
- **Fabric.js**: Provides the drawing capabilities and canvas manipulation.
- **Tailwind CSS**: For styling and responsive design.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/figma-clone.git
   cd figma-clone
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file and add the necessary API keys and configuration.

   ```bash
   LIVEBLOCKS_SECRET_KEY=your_liveblocks_secret_key
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

- **Drawing Tools**: Use the toolbar to draw shapes, text, and images on the canvas.
- **Collaboration**: Invite others to join the session and collaborate in real time.
- **Layer Control**: Manage layers to organize your design effectively.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.
