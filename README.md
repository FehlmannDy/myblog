
# Personal Blog - www.fehlmann.dev

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Website-Online-brightgreen)](https://www.fehlmann.dev)

Welcome to the GitHub repository for my personal blog built with Hugo and the [**iTheme**](https://github.com/floyd-li/hugo-theme-itheme) template. The blog is live at [www.fehlmann.dev](https://www.fehlmann.dev).


## 🚀 Key Features

- **Clean Design**: Powered by [hugo-theme-itheme](https://github.com/floyd-li/hugo-theme-itheme) with responsive layouts and dark/light mode.
- **Blog Posts**: Markdown support with code syntax highlighting.
- **SEO Optimized**: Automatic OpenGraph tags and sitemap.
- **Performance**: Fast loading times (95 Lighthouse score).
- **Social Integration**: Built-in support for GitHub and LinkedIn.


## 🛠 Tech Stack

- **Framework**: [Hugo](https://gohugo.io/) (Static Site Generator)
- **Theme**: [iTheme](https://github.com/floyd-li/hugo-theme-itheme) by Floyd Li
- **Hosting**: Deployed on [Infomaniak](https://www.infomaniak.com)
- **Styling**: Theme-default CSS with customization
- **Analytics**: Google Analytics


## 📂 Project Structure

```plaintext
blog/
├── config.toml          # Main Hugo configuration
├── content/
│   └── posts/           # All blog posts (Markdown files)
├── assets/
│   └── css/             # Custom CSS overrides
├── static/              # Images/favicons
└── themes/
    └── hugo-theme-itheme # Theme files (git submodule)
```

## 🖥 Local Development

1.  **Clone the repository** (with submodule):
   ```
    git clone --recurse-submodules https://github.com/your-username/blog.git
    cd blog
   ```
    
2.  **Install Hugo** (Extended version required):
    
    -   Follow the [official guide](https://gohugo.io/getting-started/installing/)
        
3.  **Start the server**:
    
    ```
    hugo server -D
    ```
    Access at ```http://localhost:1313```
    


## ⚙️ Theme Customization

The iTheme supports these configurations in `config.toml`:
```
[params]
  primaryColor = "#2C3E50"     # Change theme color
  avatar = "img/avatar.png"    # Profile picture
  socials = [
    { name = "github", url = "https://github.com/your-username" },
    { name = "twitter", url = "https://twitter.com/..." }
  ]
  ```


## 🤝 Contributing

While this is primarily a personal blog, you can:

-   Report issues with content/functionality via [GitHub Issues](https://github.com/FehlmannDy/myblog/issues)
    
-   Suggest improvements to the implementation
    

## 📄 License

-   Code: [MIT License](https://chat.deepseek.com/a/chat/s/LICENSE)
    
-   Content: Copyright © [FehlmannDy](https://www.fehlmann.dev)
    
-   Theme: [MIT License](https://github.com/floyd-li/hugo-theme-itheme/blob/master/LICENSE)
    

----------

🌐 **Live Site**: [www.fehlmann.dev](https://www.fehlmann.dev)  
📧 **Contact**: [dylan@fehlmann.dev](mailto:dylan@fehlmann.dev)  
📖 **Blog Posts**: [Latest Articles](https://www.fehlmann.dev/posts/)
