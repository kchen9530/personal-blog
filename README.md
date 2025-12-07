# Personal Blog

A personal technical blog featuring articles about CTF (Capture The Flag), JVM (Java Virtual Machine), Linux, Spring Framework, Web Security, and various other technical topics.

## 📚 Topics Covered

- **CTF**: Capture The Flag challenges and writeups
- **JVM**: Java Virtual Machine internals, optimization, and memory management
- **Linux**: System programming, threading, and kernel concepts
- **Spring**: Spring Framework and IoC (Inversion of Control)
- **Web Security**: XSS, security best practices, and vulnerabilities
- **Networking**: Network protocols, I/O multiplexing, and system architecture
- **Algorithms**: Data structures and competitive programming templates

## 🚀 Getting Started

### Prerequisites

- [Python 3](https://www.python.org/) (comes pre-installed on most systems)
- [Git](https://git-scm.com/) (optional, for cloning the repository)

### Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/kchen9530/personal-blog.git
   cd personal-blog
   ```

   Or simply download and extract the repository files.

## 🏃 Running Locally

This is a static website, so you can run it locally using Python's built-in HTTP server.

### Python 3

Navigate to the repository directory and run:

```bash
python3 -m http.server 8000
```

Or specify a different port:

```bash
python3 -m http.server 4000
```

### Python 2 (if Python 3 is not available)

```bash
python -m SimpleHTTPServer 8000
```

The blog will be available at:
- **http://localhost:8000** (or the port you specified)

Open the URL in your web browser to view the blog.

### Stopping the Server

Press `Ctrl+C` in the terminal to stop the server.

## 📦 Project Structure

```
personal-blog/
├── 2020/                # Blog posts from 2020
├── 2021/                # Blog posts from 2021
├── about/               # About page
├── archives/            # Archive pages
├── tags/                # Tag pages
├── css/                 # Stylesheets
├── js/                  # JavaScript files
├── images/              # Image assets
├── fancybox/            # Fancybox plugin files
└── index.html           # Main index page
```

## 🌐 Deployment

This blog is deployed to GitHub Pages. The static HTML files are hosted directly from the `master` branch.

To deploy updates, simply push changes to the repository:

```bash
git add .
git commit -m "Update blog"
git push origin master
```

GitHub Pages will automatically serve the updated content.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**kchen9530**

- GitHub: [@kchen9530](https://github.com/kchen9530)

## 🙏 Acknowledgments

- Powered by [GitHub Pages](https://pages.github.com/)
