# Gloucestershire Orchard Trust - Static Website

A complete static HTML/CSS website for the Gloucestershire Orchard Trust, ready to deploy to Netlify or any static hosting service.

## Contents

This website includes:

- **Homepage** - Welcome page with organization overview
- **Varietal Research** - Information about GOT's research programs
- **Community Orchards** - Details about community orchards in Gloucestershire
- **Apple Varieties** - Main apple varieties page plus 6 individual variety pages:
  - Ashmead's Kernel
  - Bedminster Pippin
  - Councillor
  - Eden
  - Gloucester Royal
  - Hunt's Duke of Gloucester
- **Perry Pears** - Overview of Gloucestershire's perry pear heritage
- **Plums** - Information about plum varieties in the county
- **Fruit Identification** - Details about GOT's identification service

## Deployment to Netlify

### Option 1: Drag and Drop

1. Log in to [Netlify](https://app.netlify.com/)
2. Click "Add new site" → "Deploy manually"
3. Drag the entire `static-site` folder onto the upload area
4. Your site will be live in seconds!

### Option 2: Git Integration

1. Push this repository to GitHub/GitLab/Bitbucket
2. Log in to Netlify
3. Click "Add new site" → "Import an existing project"
4. Connect your Git provider
5. Select this repository
6. Set the base directory to `static-site`
7. Leave build command empty
8. Click "Deploy site"

### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Navigate to the static-site folder
cd static-site

# Deploy
netlify deploy --prod
```

## Custom Domain

After deployment, you can add a custom domain:

1. Go to Site settings → Domain management
2. Click "Add custom domain"
3. Enter: `gloucestershireorchardtrust.org.uk`
4. Follow the DNS configuration instructions

## Features

- Fully responsive design
- Mobile-friendly navigation
- Fast loading (static HTML)
- SEO optimized
- Accessibility focused
- Green color scheme matching GOT branding (#067845)
- Lato font for headings, Verdana for body text

## File Structure

```
static-site/
├── index.html                     # Homepage
├── varietal-research.html         # Research page
├── community-orchards.html        # Community orchards
├── pears.html                     # Perry pears
├── plums.html                     # Plums
├── identification.html            # Identification service
├── varieties/
│   └── apples/
│       ├── index.html            # Apple varieties main page
│       ├── ashmeads-kernel.html
│       ├── bedminster-pippin.html
│       ├── councillor.html
│       ├── eden.html
│       ├── gloucester-royal.html
│       └── hunts-duke-of-gloucester.html
├── css/
│   └── style.css                 # Main stylesheet
├── netlify.toml                  # Netlify configuration
└── README.md                     # This file
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Content © 2025 Gloucestershire Orchard Trust. All rights reserved.

## Support

For questions or issues with the website, please contact the Gloucestershire Orchard Trust.
