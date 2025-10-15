# 🎧 Musify Frontend

The **Musify Frontend** is a web application that complements the [Musify Backend](https://github.com/SebiB24/MusifyBackend).  
It provides an intuitive, Spotify-like user interface for managing music data — artists, albums, songs, and playlists — built with **Angular** and **TypeScript**.

This project was developed as part of a **team internship project at AROBS**.

---

## 🚀 Features

- 🎵 **View and search** songs, albums, artists, and playlists  
- 🧑‍🎤 **Manage music library** – create artists, albums, playlists, and songs  
- 📚 **User dashboard** with personal library and playlists  
- 🔍 **Search bar** with instant filtering  
- 🎨 **Responsive and modern UI** inspired by Spotify  
- 🔐 **Integration with Musify Backend** for authentication and data management  

---

## 🧱 Project Structure

musify-frontend/  
├── src/  
│ ├── app/  
│ │ ├── components  
│ │ ├── core/ # Shared services, interceptors, guards  
│ │ ├── app.component.html  
│ │ ├── app.component.scss  
│ │ ├── app.component.ts  
│ │ ├── app.component.spec.ts  
│ │ ├── app.config.ts  
│ │ ├── app.routes.ts  
│ ├── assets/ # Static assets (icons, images, etc.)  
│ ├── environments/  
│ │ └── environments.ts  
│ ├── index.html  
│ ├── main.ts  
│ ├── styles.scss  
│ ├── web.config  
│ └── test-results/  
├── angular.json  
├── package.json  
├── tsconfig.json  
└── README.md  


---

## 🖥️ Application Overview

The **Home Page** provides an overview of the user’s music collection and recommendations.  

### 🏠 Main Sections
- **Discover**: Navigate through Home and Songs  
- **Your Library**: Browse Artists, Albums, and Playlists  
- **Manage**: Create Albums, Artists, Songs, and access the User Dashboard  

### 🔍 Search Bar
Search for songs, artists, or albums instantly from the top navigation bar.

### 🎨 UI Highlights
- Modern **Spotify-inspired** layout  
- Responsive **Angular Material-based** design  
- Dynamic content loading with smooth transitions  

---

## ⚙️ Technologies Used

- **Angular 17+**
- **TypeScript**
- **SCSS**
- **Angular Material**
- **RxJS**
- **HTML5 / CSS3**
- **Node.js** for development environment
- **Integration with Spring Boot Musify Backend**

---

## 🔗 Backend Integration

The frontend communicates with the Musify backend REST API.  
Make sure the backend is running locally (default: `http://localhost:8080`) before starting the frontend.

You can find the backend here:  
👉 [Musify Backend Repository](https://github.com/SebiB24/MusifyBackend)

---

## 🧪 Running the Application

### 1️⃣ Prerequisites
- Node.js 18+
- Angular CLI

### 2️⃣ Install Dependencies

npm install

### 3️⃣ Start the Development Server
ng serve

## 📸 Preview

### 🏠 Home Page
Displays top songs, favorite artists, and hot albums:

<img width="2539" height="1264" alt="image" src="https://github.com/user-attachments/assets/2c8b1529-0266-40f4-a4b4-d8b7114d0e6c" />


---




