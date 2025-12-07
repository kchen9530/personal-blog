# Personal Blog

A personal technical blog built with [Hexo](https://hexo.io/), featuring articles about CTF (Capture The Flag), JVM (Java Virtual Machine), Linux, Spring Framework, Web Security, and various other technical topics.

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

- [Node.js](https://nodejs.org/) (v12.0 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git](https://git-scm.com/)

### Installation

1. **Install Hexo CLI globally:**
   ```bash
   npm install hexo-cli -g
   ```

2. **Clone this repository:**
   ```bash
   git clone https://github.com/kchen9530/personal-blog.git
   cd personal-blog
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Install Hexo Git Deployer (if you want to deploy):**
   ```bash
   npm install hexo-deployer-git --save
   ```

## 🏃 Running Locally

To run the blog locally for development:

```bash
hexo server
```

Or use the short form:

```bash
hexo s
```

The blog will be available at `http://localhost:4000` by default.

## 📝 Configuration

The main configuration file is `_config.yml`. For deployment, configure the deploy section:

```yaml
deploy:
  type: git
  repo: https://github.com/kchen9530/personal-blog.git
  branch: master
```

## 🛠️ Common Commands

- **Generate static files:**
  ```bash
  hexo generate
  # or
  hexo g
  ```

- **Start local server:**
  ```bash
  hexo server
  # or
  hexo s
  ```

- **Deploy to GitHub Pages:**
  ```bash
  hexo deploy
  # or
  hexo d
  ```

- **Clean cache and generated files:**
  ```bash
  hexo clean
  ```

- **Generate and deploy in one command:**
  ```bash
  hexo generate --deploy
  # or
  hexo g -d
  ```

## 📦 Project Structure

```
personal-blog/
├── _config.yml          # Hexo configuration
├── source/              # Source files (if using Hexo source)
├── themes/              # Theme files (if using custom theme)
├── public/              # Generated static files
├── 2020/                # Blog posts from 2020
├── 2021/                # Blog posts from 2021
├── archives/            # Archive pages
├── tags/                # Tag pages
├── css/                 # Stylesheets
├── js/                  # JavaScript files
├── images/              # Image assets
└── index.html           # Main index page
```

## 🌐 Deployment

This blog is deployed to GitHub Pages. The static HTML files are generated and pushed to the `master` branch.

To deploy manually:

```bash
hexo clean
hexo generate
hexo deploy
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**kchen9530**

- GitHub: [@kchen9530](https://github.com/kchen9530)

## 🙏 Acknowledgments

- Built with [Hexo](https://hexo.io/)
- Powered by [GitHub Pages](https://pages.github.com/)

