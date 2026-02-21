# ADM Civil Website

A sleek, professional landing page for ADM Civil — civil construction done differently in South East Queensland.

## Deployment to Vercel

### Option 1: GitHub + Vercel (Recommended)

1. Create a new repository on GitHub
2. Push this folder to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/adm-civil-website.git
   git push -u origin main
   ```
3. Go to [vercel.com](https://vercel.com) and sign in
4. Click "Add New Project"
5. Import your GitHub repository
6. Click "Deploy" — no configuration needed

### Option 2: Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Run from this directory:
   ```bash
   vercel
   ```
3. Follow the prompts

## Adding the Capability Statement

The site includes download buttons for a capability statement PDF. To add yours:

1. Name your PDF file `ADM-Capability-Statement.pdf`
2. Place it in the root folder alongside `index.html`

The download buttons in the hero and capability sections will then work automatically.

## Project Structure

```
adm-website/
├── index.html                    # Main landing page (all CSS embedded)
├── ADM-Capability-Statement.pdf  # Add your capability statement here
├── vercel.json                   # Vercel deployment config
└── README.md                     # This file
```

## Customisation

All styles are embedded in `index.html` within the `<style>` tag. Key colour variables are defined at the top:

- `--orange-600`: Primary accent colour (matches ADM branding)
- `--zinc-950`: Main background
- `--zinc-900`: Section backgrounds

To add team photos, replace the SVG placeholders in the team section with `<img>` tags.

## Contact

Contact details are set to:
- Phone: 0412 903 786
- Email: info@admcivil.com.au
- Address: 42 Avington Street, Keperra QLD
- ACN: 694 391 458
