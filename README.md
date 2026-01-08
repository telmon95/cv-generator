# CV Generator

A professional, open-source CV/Resume generator that automatically fetches your GitHub projects and creates a beautiful, downloadable CV.

## Features

- **GitHub Integration** - Automatically fetch your repositories and their details
- **Professional Design** - Clean, modern layout suitable for ATS systems
- **Fullstack & DevOps Focus** - Pre-configured sections for both roles
- **Printable to PDF** - Optimized for printing/downloading
- **No Backend Required** - Pure HTML, CSS, and JavaScript
- **Customizable** - Easy to edit and personalize

## Quick Start

1. Open `cv-generator.html` in your browser
2. Enter your GitHub username and click "Fetch Projects from GitHub"
3. Fill in your personal information
4. Select which projects to include
5. Click "Generate CV" to view your CV
6. Print to PDF using your browser's print function (Ctrl+P / Cmd+P)

## Installation

### Option 1: Direct Use
Simply open `cv-generator.html` in your browser - no installation needed!

### Option 2: Local Server (Recommended)
```bash
# Using npx serve
npx serve .

# Or using Python
python3 -m http.server 8000

# Or using Node.js http-server
npx http-server
```

Then open `http://localhost:3000/cv-generator.html` in your browser.

## Usage

1. **Enter GitHub Username**: Type your GitHub username in the form
2. **Fetch Projects**: Click "Fetch Projects from GitHub" to load your repositories
3. **Select Projects**: Check/uncheck projects you want to include in your CV
4. **Fill Personal Info**: Add your name, email, phone, location, LinkedIn, etc.
5. **Add Summary**: Write your professional summary
6. **Add Skills**: List your technical skills (comma-separated)
7. **Generate CV**: Click "Generate CV" to create and view your CV
8. **Download PDF**: Use browser's print function to save as PDF

## Sections Included

- Professional Summary
- Technical Skills (Frontend, Backend, DevOps, Tools)
- Projects (with GitHub links)
- Professional Experience
- Education
- Additional Information

## Customization

### Edit the CV Template
Open `cv.html` and customize:
- Colors and styling in the `<style>` section
- Section headings and content
- Layout and structure

### Add Custom Projects
Use the "Add Project" button in the generator to manually add projects not on GitHub.

## Browser Compatibility

- Chrome/Edge (Recommended)
- Firefox
- Safari
- Opera

## Tips

- **Print to PDF**: Use Chrome or Firefox's print function (Ctrl+P / Cmd+P) and select "Save as PDF"
- **ATS Friendly**: The CV is formatted to pass Applicant Tracking Systems
- **GitHub Rate Limits**: GitHub API has rate limits. If you hit the limit, wait an hour or use a GitHub token
- **Customization**: Edit the HTML directly to match your preferred style

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - feel free to use this for personal or commercial projects.

## Support

If you encounter any issues or have suggestions, please open an issue on GitHub.

---

**Made with ❤️ for developers who want a professional CV without the hassle**
