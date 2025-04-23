# Dodo: A Lightweight File Manager API  

🚀 **Dodo** is a simple yet powerful **file manager API** designed to handle file operations like uploads, downloads, organization, and metadata management. Built with **Node.js** and **Express**, it provides a RESTful interface for managing files programmatically, making it ideal for developers who need a backend file system for their applications.  

## ✨ Key Features  

✔ **File Upload & Download** – Easily upload and retrieve files via API endpoints.  
✔ **Folder Management** – Create, list, and delete directories.  
✔ **File Metadata** – Track file details (name, size, type, last modified).  
✔ **Search & Filter** – Find files by name, type, or date.  
✔ **Authentication (Optional)** – Secure endpoints with JWT or API keys.  
✔ **Scalable Storage** – Supports local storage (with future cloud integration).  

## 🛠 Tech Stack  
- **Backend:** Python  
- **Database (Optional):** MongoDB (for metadata storage), Postgresql, AWS S3  
- **Authentication:** JWT (optional)  
- **File Storage:** Local file system (expandable to AWS S3, Firebase, etc.)  

## 🚀 Getting Started  

### Prerequisites  
- Python 3.10
- Node.js (v16+)  
- npm/yarn  
- (Optional) MongoDB (if using metadata storage)  

### Installation  
1. Clone the repo:<br>
   git clone https://github.com/ArnabAdhikary/dodo.git<br>
   cd dodo<br>

### Install dependencies:
2. npm install

### Configure .env (copy .env.example):
3. env<br>
PORT=3000<br>
FILE_STORAGE_PATH=./uploads<br>

### (Optional) MongoDB & JWT settings
Run the server:<br>
npm start<br>

### API Endpoints
Method	Endpoint	Description<br>
POST	/upload	Upload a file<br>
GET	/files	List all files<br>
GET	/files/:filename	Download a file<br>
DELETE	/files/:filename	Delete a file<br>
POST	/folders	Create a folder

### 🔧 Future Enhancements
Cloud Storage Integration (AWS S3, Google Drive)<br>
File Preview Generation (PDFs, images)<br>
User Permissions (Role-based access control)<br>
CLI Tool for local file management<br>
