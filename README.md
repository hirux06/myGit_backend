# MyGit - Simplified Repository Manager

MyGit is a lightweight, user-friendly Git alternative that simplifies repository management with essential Git-like functionalities, offering an intuitive CLI interface and seamless cloud integration.

## 🚀 Features

- 🗂 **Version Control Made Easy**: Supports essential Git operations like `add`, `stage`, `commit`, `push`, `pull`, and `revert`.
- ☁️ **Cloud Integration**: Secure file storage and retrieval with AWS S3.
- 📜 **RESTful API**: Exposes endpoints for core Git functionalities.
- 🔐 **Secure Storage**: Ensures data integrity and accessibility.
- 🖥 **CLI Interface**: Simplifies repository management with intuitive commands.

## 🏗 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Storage**: AWS S3
- **API**: RESTful architecture
- **Authentication**: JWT-based security

## 📂 Project Structure

```
mygit/
│── backend/
│   ├── models/        # Database schemas
│   ├── routes/        # API routes
│   ├── controllers/   # Business logic
│   ├── cli/           # Command-line interface logic
│   ├── storage/       # AWS S3 integration
│   ├── server.js      # Entry point
│
│── README.md
```

## 🔧 Installation & Setup

### Prerequisites
- Node.js & npm
- MongoDB
- AWS S3 Bucket

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mygit.git
   cd mygit
   ```
2. **Install dependencies**
   ```bash
   cd backend && npm install
   ```
3. **Set up environment variables** (Create a `.env` file in the backend)
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   AWS_ACCESS_KEY=your_aws_access_key
   AWS_SECRET_KEY=your_aws_secret_key
   AWS_BUCKET_NAME=your_bucket_name
   ```
4. **Run the backend server**
   ```bash
   cd backend
   npm start
   ```
5. **Start using MyGit CLI**
   ```bash
   node cli/mygit.js --help
   ```

## 🛠 Usage

### Initialize a repository
```bash
node cli/mygit.js init
```

### Add and commit files
```bash
node cli/mygit.js add file.txt
node cli/mygit.js commit -m "Initial commit"
```

### Push and pull changes
```bash
node cli/mygit.js push
node cli/mygit.js pull
```

## 🌟 Future Enhancements
- 🌍 Multi-cloud storage support (Google Drive, Dropbox)
- 📢 Notifications for repository updates
- 💡 AI-powered commit message suggestions

## 📜 License

This project is licensed under the MIT License.

## 🤝 Contributing
Pull requests are welcome! For major changes, open an issue first to discuss improvements.

## 📞 Contact
For inquiries, reach out to **Saran Hiruthik** at [saran.hiruthik83@gmail.com](mailto:saran.hiruthik83@gmail.com) or connect via [LinkedIn](https://linkedin.com/in/saran-hiruthik-m).

