# Movies React App

This project was generated with:
- React.js
- Appwrite
- Tailwind CSS

## Prerequisites

Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

## Installation

Install the project dependencies using npm:

```bash
npm install
```

##Set Up Environment Variables
Create a new file named `.env.local` in the root of your project and add the following content:

```env
VITE_IMDB_API_KEY=

VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_COLLECTION_ID=
```

Replace the placeholder values with your actual **[TheMovieDatabase API](https://developer.themoviedb.org/reference/intro/getting-started)** and **[Appwrite](https://apwr.dev/JSM050)** credentials. You can obtain these credentials by signing up on the [TheMovieDatabase](https://developer.themoviedb.org/reference/intro/getting-started) and creating a new project on the [Appwrite](https://apwr.dev/JSM050)

## Running

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.