# Arch Vending Website

A modern, responsive website for Arch Vending, a St. Louis-based vending machine company. Built with Jekyll and Bootstrap 5.

## Features

- **Modern Design**: Clean, professional design using Bootstrap 5
- **Responsive**: Mobile-friendly across all devices
- **Jekyll-based**: Easy to maintain and update
- **SEO Optimized**: Built-in SEO features and meta tags
- **Contact Forms**: Integrated contact forms for lead generation
- **Service Areas**: Comprehensive coverage of St. Louis metro area
- **Multiple Service Types**: Traditional vending, kiosks, and honor boxes

## Pages

- **Home**: Landing page with hero section, services overview, and testimonials
- **Services**: Detailed information about vending solutions
- **Service Areas**: Complete coverage map with zip codes
- **About**: Company history, mission, and team information
- **Contact**: Contact form and business information

## Technology Stack

- **Jekyll**: Static site generator
- **Bootstrap 5**: CSS framework
- **Bootstrap Icons**: Icon library
- **Google Fonts**: Typography (Inter font family)
- **Fathom Analytics**: Privacy-focused analytics
- **Google Analytics**: Website tracking

## Setup Instructions

### Prerequisites

- Ruby (version 2.6 or higher)
- RubyGems
- Bundler

### Installation

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd archvending-website
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the website**
   Open your browser and navigate to `http://localhost:4000`

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## Customization

### Colors

The website uses a custom color scheme based on the Arch Vending logo:

- **Primary**: Dark Blue (#353C56)
- **Secondary**: Light Blue (#62ABA2)
- **Accent**: Red (#ED1E44)
- **Highlight**: Yellow/Gold (#FED766)

Colors can be modified in `_config.yml` under the `colors` section.

### Content

- **Site Configuration**: Edit `_config.yml` for site-wide settings
- **Pages**: Each page is a separate HTML file with Jekyll front matter
- **Navigation**: Update the `navigation` section in `_config.yml`
- **Contact Information**: Update contact details in `_config.yml`

### Images

- Logo files are stored in the `images/` directory
- Multiple logo variations are available for different use cases
- Images are optimized for web use

## File Structure

```
archvending-website/
├── _config.yml          # Jekyll configuration
├── _layouts/            # Jekyll layouts
│   └── default.html     # Main layout template
├── _includes/           # Jekyll includes (if needed)
├── _sass/              # Sass files (if needed)
├── images/             # Image assets
├── index.html          # Homepage
├── services.html       # Services page
├── areas.html          # Service areas page
├── about.html          # About page
├── contact.html        # Contact page
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## SEO Features

- Meta descriptions for each page
- Open Graph tags for social media sharing
- Structured data markup
- XML sitemap generation
- Robots.txt file

## Analytics

The website includes:

- **Fathom Analytics**: Privacy-focused analytics (already configured)
- **Google Analytics**: Standard website tracking (already configured)

## Contact Information

Update the following in `_config.yml`:

```yaml
contact:
  phone: "(314) 555-0123"
  email: "info@archvending.com"
  address: "St. Louis, MO"

social:
  facebook: "https://facebook.com/archvending"
  twitter: "https://twitter.com/archvending"
  linkedin: "https://linkedin.com/company/archvending"
```

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select the main branch as source
4. The site will be available at `https://[username].github.io/[repository-name]`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `bundle exec jekyll build`
3. Set publish directory: `_site`
4. Deploy automatically on git push

### Other Hosting

Build the site locally and upload the `_site` directory to your web server.

## Maintenance

### Regular Updates

- Update contact information as needed
- Add new service areas or zip codes
- Update testimonials and customer reviews
- Refresh content and images periodically

### Security

- Keep Jekyll and dependencies updated
- Regularly review and update contact forms
- Monitor analytics for unusual activity

## Support

For technical support or questions about the website, contact the development team.

## License

This project is proprietary to Arch Vending. All rights reserved.

---

**Arch Vending** - Professional vending solutions for the St. Louis metro area.