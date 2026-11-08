# Blog Post Application

A full-featured blogging platform built with HTML, CSS, and JavaScript. Allows users to create, read, and manage blog posts with authentication.

## Features

- 📝 **Create & Publish Posts** - Rich text editor for blog content
- 👤 **User Authentication** - Login and registration system
- 📱 **Responsive Design** - Works on desktop and mobile
- 🏠 **Blog Wall** - Browse all published posts
- 🔒 **User Dashboard** - Manage your posts and profile

## Pages

| File | Purpose |
|------|---------|
| `Opening_page.html` | Landing page with welcome message |
| `login_page.html` | User login interface |
| `register_page.html` | New user registration |
| `home.html` | Main blog feed/wall |
| `blog_wall.html` | Display all posts |
| `add-post.html` | Create new blog post |
| `post.html` | Individual post view |

## Technologies

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Node.js (if using app.js server)
- **Architecture:** Client-side rendering

## Quick Start

### Option 1 — Static HTML (No server required)
```bash
# Open directly in browser
Opening_page.html
```

### Option 2 — With Node.js Server
```bash
# Install dependencies (if package.json exists)
npm install

# Start server
node app.js

# Open browser to
http://localhost:3000
```

## Project Structure

```
AWT_Project_Blog_Post_App/
├── Opening_page.html       # Landing page
├── login_page.html         # Authentication
├── register_page.html      # User signup
├── home.html              # Main dashboard
├── blog_wall.html         # Post feed
├── add-post.html          # Create post
├── post.html              # View post
├── app.js                 # Server (if using Node)
└── .gitignore            # Git ignore rules
```

## Features in Detail

### User Authentication
- Secure login and registration
- Session management
- Password validation

### Blog Post Management
- Create posts with title and content
- Edit and delete your posts
- Browse all posts by all users

### Responsive Design
- Mobile-friendly interface
- Adaptive layouts
- Touch-friendly navigation

## Development

```bash
# Clone repository
git clone <your-repo-url>
cd AWT_Project_Blog_Post_App

# Open in browser or start server
# Make changes and test locally
```

## Course Information

**Course:** Advanced Web Technologies (AWT)  
**Project Type:** Academic Web Application  
**Institution:** GSFC University  

## Future Enhancements

- [ ] Database integration (MySQL/MongoDB)
- [ ] Rich text editor
- [ ] Image upload support
- [ ] Comment system
- [ ] Post categories/tags
- [ ] Search functionality
- [ ] User profiles with avatars

## License

Academic project - GSFC University

## Author

**Dhruvin Jayswal** (23BT04026)  
B.Tech Computer Science Engineering  
GSFC University

---

*Built as part of Advanced Web Technologies coursework*
