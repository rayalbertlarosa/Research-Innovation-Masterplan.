# Research Innovation Masterplan Visualization

An interactive web-based visualization of the Research Innovation Masterplan, featuring comprehensive implementation plans organized by strategic pillars.

## 🚀 Live Demo

Once deployed, your visualization will be available at:
`https://[your-username].github.io/[repository-name]/`

## 📋 Files Required for Deployment

- `index.html` - Main visualization page (self-contained with all CSS and JavaScript)
- `animo-logo.png` - Logo image used in the header and footer

## 🌐 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., "masterplan-visuals")
5. Choose "Public" (required for free GitHub Pages)
6. Click "Create repository"

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html`
   - `animo-logo.png`
3. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
# Initialize git in your project folder
git init

# Add files
git add index.html animo-logo.png

# Commit files
git commit -m "Initial commit: Add masterplan visualization"

# Add remote repository (replace with your repository URL)
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to "Settings"
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"
6. Wait 1-2 minutes for deployment to complete
7. Your site will be live at: `https://[your-username].github.io/[repository-name]/`

## ✨ Features

- **Interactive Pillar Cards**: Click on any of the 6 strategic pillars to explore detailed implementation plans
- **Comprehensive Plan Details**: View objectives, expected outcomes, KPIs, and step-by-step implementation details
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Professional Styling**: Modern green gradient theme with smooth animations

## 📁 Project Structure

```
.
├── index.html          # Main visualization page
├── animo-logo.png      # Logo image
└── README.md          # This file
```

## 🎯 Strategic Pillars

1. **Research Infrastructure & Capacity Development**
2. **Human Capital & Capability Building**
3. **Governance & Compliance Excellence**
4. **Innovation & Knowledge Creation**
5. **Strategic Partnerships & Collaboration**
6. **Digital Transformation & Research Analytics**

## 🛠️ Technical Details

- **Framework**: Pure HTML, CSS, and JavaScript (no dependencies)
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Self-Contained**: All styles and scripts are embedded in the HTML file
- **No Build Process**: Ready to deploy as-is

## 📝 Customization

To customize the visualization:

1. Edit `index.html` directly
2. All styles are in the `<style>` section (lines 7-757)
3. All JavaScript is in the `<script>` section (lines 4004-4385)
4. Replace `animo-logo.png` with your own logo (120x120px recommended)

## 🔄 Updating the Site

After making changes:

**Using GitHub Web Interface:**
1. Go to your repository on GitHub
2. Click on the file you want to update
3. Click the pencil icon to edit
4. Make your changes
5. Click "Commit changes"

**Using Git:**
```bash
git add .
git commit -m "Update visualization"
git push
```

Changes will be live within 1-2 minutes.

## 📧 Support

For issues or questions about the visualization, please create an issue in the GitHub repository.

## 📄 License

This project is part of the Research Innovation Masterplan initiative.

---

**Ready to launch!** Follow the deployment steps above to make your visualization live on GitHub Pages.
