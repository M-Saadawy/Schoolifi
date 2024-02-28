# Schoolifi

Schoolifi is a simple and elegant website template for creating online courses and educational content. It is designed to be easy to use, customize, and deploy. It is compatible with GitHub Pages and other static site generators.

## Features

- Responsive and mobile-friendly design
- Minimal and clean layout
- Markdown support for writing course content
- Syntax highlighting for code snippets
- Navigation menu and breadcrumbs for easy navigation
- Footer with social media links and contact information

## Demo

You can see a live demo of Schoolifi [here](^4^).

## Installation

To use Schoolifi, you need to have [Git](^5^) installed on your computer. You can clone this repository or download it as a ZIP file.

```bash
# Clone this repository
git clone https://github.com/your-username/schoolifi.git

# Go to the project directory
cd schoolifi
```

## Usage

To create your own courses and content, you need to edit the files in the `docs` folder. You can use any text editor or markdown editor to write your content. The files are organized as follows:

- `index.md`: This is the homepage of your website. You can edit the title, subtitle, and introduction of your website here.
- `about.md`: This is the about page of your website. You can edit the information about yourself, your background, and your goals here.
- `courses`: This is the folder where you store your course content. Each subfolder represents a course, and each file represents a lesson. You can create as many courses and lessons as you want. You can also add images, videos, and other resources to your lessons. To link to a lesson, use the relative path of the file, such as `[Lesson 1](courses/course-1/lesson-1.md)`.
- `config.yml`: This is the configuration file of your website. You can edit the site title, description, theme, logo, favicon, and other settings here.
- `style.css`: This is the custom stylesheet of your website. You can edit the colors, fonts, and other styles here.

To preview your website locally, you can use a tool like [docsify](^6^), which is a simple and lightweight documentation generator. You can install it using [npm](^7^), which is a package manager for JavaScript.

```bash
# Install docsify globally
npm i docsify-cli -g

# Serve the docs folder
docsify serve docs
```

You can then access your website at `http://localhost:3000`.

To deploy your website to GitHub Pages, you need to push your changes to the `master` branch of your repository. You also need to enable GitHub Pages in the settings of your repository, and select the `docs` folder as the source. You can then access your website at `https://your-username.github.io/schoolifi`.

## Contributing

Schoolifi is an open source project, and contributions are welcome. If you want to report a bug, request a feature, or suggest an improvement, please open an issue. If you want to submit a pull request, please fork this repository and create a new branch for your changes.

## License

Schoolifi is licensed under the [MIT License](^8^), which means you can use, copy, modify, distribute, and sell it without any restrictions or conditions. However, a credit or a link back to this repository would be appreciated. 😊
