# Description

Welcome to my personal portfolio website! This website is designed to serve as a showcase of my education, skills, and experiences in a visually appealing and informative manner. Whether you're a potential employer, a colleague, or someone interested in my projects, this portfolio offers an insight into who I am and what I do.

# Table of Contents
- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Support and Contact](#support-and-contact)
- [License](#license)
- [Acknowledgments](#acknowledgments)

# Features

This personal portfolio website comes with a range of features and functionalities to showcase my work and make the user experience engaging and informative. Here are some of the key features:

- Responsive Design
- Portfolio Showcase
- Customizable Theme
- Writing Samples (Blog Section) 
- Contact Information
- Interactive Elements
- Analytics & Optimization
- Fast Loading

# Technologies Used

- [Hugo](https://github.com/gohugoio/hugo)
- [Hugo Profile](https://github.com/gurusabarish/hugo-profile) (Theme)
- Go
- HTML/CSS
- JavaScript
- GitHub Pages

# Installation

To get started with your Hugo website, follow these steps:

## 1. Install Hugo

First, you need to install Hugo. You can download the latest version from the [Hugo releases page](https://github.com/gohugoio/hugo/releases).

## 2. Verify Installation

After installation, open your terminal and run the following command to ensure Hugo is installed correctly:

```bash
hugo version
```

   You should see the installed Hugo version displayed.

## 3. Create a New Hugo Site

Navigate to the directory where you want to create your Hugo website. Run the following command to create a new site:

```bash
hugo new site my-portfolio
```

Replace `my-portfolio` with the name of your website.

## 4. Choose a Theme

You can use one of the available Hugo themes or create a custom theme. To add a theme, navigate to your site's root directory and run:

```bash
git init
git submodule add <theme-repository-url> themes/<theme-name>
```

## 5. Configure Your Website

Navigate to your site's root directory. Edit the `config.toml` file to configure site settings, including theme selection, title, and other options.

Note that newer versions of Hugo recommend naming the configuration file to `hugo.toml`

## 6. Create Content

Hugo uses content files in Markdown format. You can create new content by running:

```bash
hugo new posts/my-first-post.md
```

Replace `my-first-post.md` with your desired content file name.

## 7. Start the Hugo Server

To preview your site locally, run the Hugo server with the following command:

```bash
hugo server -D
```

The `-D` flag enables draft content to be displayed.

## 8. Access Your Site Locally

Open a web browser and go to `http://localhost:1313` to see your website locally. You can make changes, and the server will automatically refresh the site.

# Usage

### Theme Customization

The website's theme can be customized to reflect your personal branding and style. If you would like the follow this website, use the [Hugo-Profile](https://github.com/gurusabarish/hugo-profile)theme. To add a template, follow these steps:

1. Navigate to your website's root directory.
2. Find the theme you are using. Themes are typically located in the `themes` directory.
3. Customize the theme's settings by modifying the theme's configuration files (typically `hugo.toml`, but `config.toml` is also used).
4. You can explore other Hugo themes available on the Hugo Themes website ([https://themes.gohugo.io/](https://themes.gohugo.io/)). Follow the theme's documentation for installation and customization instructions.

### Content Customization

You can personalize the content of your website to showcase your work, projects, and expertise. Here's how:

1. Navigate to your website's root directory.
2. Update the Markdown content files located in the `content` directory. These files represent the pages and content on your website.
3. Add new content files to create additional pages or sections as needed. For example, to add a new project, create a Markdown file in the appropriate content directory and add the project details.
4. Customize the front matter of each content file to provide titles, descriptions, and any other metadata.
5. Insert images and media into your content using Markdown syntax. You can place image files in the appropriate directories and reference them in your content files.
6. Configure navigation menus and links in your website's configuration file (usually `config.toml`). You can add or remove menu items and specify their order.

### Layout Customization

Refer to the [hugo-profile theme guidelines](https://themes.gohugo.io/themes/hugo-profile/) for layout customization guidelines.

### Configuration Customization

Fine-tune your website's settings and configurations to meet your specific needs:

1. Edit the `config.toml` file in the root directory to make adjustments to site-wide settings, SEO metadata, and social media links.
2. Configure Hugo's site parameters, such as the site title, description, language, and timezone.
3. You can also enable or disable various features like Google Analytics, Disqus comments, and other integrations.

Refer to the [hugo-profile theme guidelines](https://themes.gohugo.io/themes/hugo-profile/) for additional customization guidelines. Remember to rebuild your website using `hugo` after making changes to see the updates reflected on the live site.

# Deployment

This portfolio website was deployed using [GitHub Pages](https://pages.github.com/). Follow this guide to deploy your website:

### 1. Push Your Website Files to the Repository

Push your Hugo website source code to the GitHub repository you've just created. You can use Git to do this.

```bash
# Initialize a Git repository in your project folder
git init

# Add all files to the repository
git add .

# Commit the changes
git commit -m "Initial commit"

# Add the GitHub repository as a remote (replace 'your-username' and 'your-repo' with the appropriate values)
git remote add origin https://github.com/your-username/your-repo.git

# Push your code to the repository
git push -u origin master
```

### 2. Build Your Website

Before deploying, you need to build your Hugo website by generating the static HTML files. In your project directory, run:

```bash
hugo
```

This command will create a `public` directory with your generated website files.

### 3. GitHub Pages Configuration

To configure GitHub Pages for your repository, refer to the [Hugo documentation](https://gohugo.io/hosting-and-deployment/hosting-on-github/) for the steps to configure GitHub Pages and create an workflow action.

### 4. Access Your Website

Your website will be available at `https://your-username.github.io/your-repository`. It may take a few minutes for the changes to propagate.

### 5. Custom Domain (Optional)

If you want to use a custom domain (eg. [example.com](http://www.example.com)), you can configure it in the GitHub Pages settings. Make sure to set up the necessary DNS records for your custom domain to [point to GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site). 

# Support and Contact

If you have general inquiries, feedback, or suggestions for improvements, please feel free to contact me using the provided email in the "Contact" section of the website. I'll get back to you as soon as possible.

Alternatively, you can connect with me on social media:
- [Twiiter](https://twitter.com/blipovski)
- [LinkedIn](https://linkedin/in/blipovski)
- [GitHub](https://github.com/blipovski)

# License

This personal portfolio website is open-source and is available under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). Please refer to the `license` file included with this repository.

# Acknowledgments

I would like to express my gratitude to the following individuals, projects, and resources that have contributed to the development of this personal portfolio website:

- **[Hugo](https://gohugo.io/hosting-and-deployment/hosting-on-github/)**
	A special thanks to the developers of Hugo for providing a fast and flexible static site generator that powers this website.
- **[Hugo-Profile](https://themes.gohugo.io/themes/hugo-profile/) Theme (authored by [Gurusabarish](https://www.linkedin.com/in/gurusabarish/)**
	The creators of the Hugo themes used in this project, which have significantly influenced the website's design and layout.
- **My Supporters**
	Most importantly, a big thank you to my supporters, colleagues, friends, and family who have assisted be throughout this project.
