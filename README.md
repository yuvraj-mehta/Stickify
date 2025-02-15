# Notes Application

This is a simple notes application built with **React** and **Vite**. It allows users to create, update, delete, and manage notes with different colors. The application uses **Appwrite** as the backend service for managing notes.

## Features
- 📝 **Create new notes**
- ✏️ **Update existing notes**
- 🗑 **Delete notes**
- 🎨 **Change note colors**
- 🔀 **Drag and drop notes to reposition them**
- 📱 **Responsive design**

## Project Structure
```
.env
.gitignore
eslint.config.js
index.html
package.json
public/
  vite.svg
README.md
src/
  App.jsx
  appwrite/
    config.js
    databases.js
  assets/
    colors.json
    fakeData.js
    react.svg
  components/
    AddButton.jsx
    Color.jsx
    Controls.jsx
    DeleteButton.jsx
    NoteCard.jsx
  context/
    NoteContext.jsx
  icons/
    Plus.jsx
    Spinner.jsx
    Trash.jsx
  index.css
  main.jsx
  pages/
    NotesPage.jsx
  utils.js
vite.config.js
```

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/notes-app.git
   cd notes-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Create a `.env` file in the root directory and add your Appwrite credentials:**
   ```sh
   VITE_ENDPOINT=https://cloud.appwrite.io/v1
   VITE_PROJECT_ID=your_project_id
   VITE_DATABASE_ID=your_database_id
   VITE_COLLECTION_NOTES_ID=your_collection_id
   ```

### Running the Application
```sh
npm run dev
# or
yarn dev
```
Open your browser and navigate to **[http://localhost:5173](http://localhost:5173)** to see the application in action.

## Building for Production
To build the application for production, run:
```sh
npm run build
# or
yarn build
```
The production-ready files will be in the `dist` directory.

<!-- ## Linting
To lint the code, run:
```sh
npm run lint
# or
yarn lint
``` -->

## Previewing the Production Build
To preview the production build, run:
```sh
npm run preview
# or
yarn preview
```

## Project Configuration

### Vite Configuration
The Vite configuration is located in `vite.config.js`. It includes the React plugin for Vite.

<!-- ### ESLint Configuration
The ESLint configuration is located in `eslint.config.js`. It includes recommended rules for JavaScript and React. -->

## Contributing
Contributions are welcome! Please open an **issue** or submit a **pull request** for any changes.

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## Acknowledgements
- 🚀 [Vite](https://vitejs.dev/)
- ⚛️ [React](https://reactjs.org/)
- ☁️ [Appwrite](https://appwrite.io/)

## Contact
For any questions or inquiries, please contact **mehtayuvraj532@gmail.com**.

---

This README provides an overview of the project, instructions for getting started, and details about the project configuration. Feel free to customize it further based on your specific needs. 🚀
## Credits
Made with ❤️ by **Yuvraj Mehta**
