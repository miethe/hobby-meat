# Hobby Meat - The Distracted Hobbyist

**Tagline:** *"I'll finish the garage tomorrow."*

Welcome to **Hobby Meat** (also known as **Distracted Hobbyists** or **Meatopedia**) - a personal knowledge base documenting in-depth research across a wide variety of hobbies and interests.

## About

This site exists to organize and share the extensive research accumulated over the years on everything from home audio and telescopes to 3D printing and smart homes. If you're someone who collects hobbies faster than you complete them, you're in good company!

The philosophy is simple: while a hobby might be temporarily abandoned, the research invested in becoming an "overnight expert" shouldn't be wasted. If someone else can benefit from that knowledge, the time was well spent!

**Live Site:** [distractedhobbyists.com](https://distractedhobbyists.com)

## Content Categories

- **AV**: Speakers, Headphones, Amplifiers, Displays, Home Theater
- **Auto**: Vehicles and automotive topics
- **Careers**: Consulting, IT Architecture, Solution Engineering
- **Gaming**: Board games and video games
- **Learning**: Books, Podcasts, Educational resources
- **Life**: Finance, Food & Drink, Lifestyle
- **Makers**: 3D Printing, DIY Projects, Photography, Woodworking
- **Outdoors**: Beach, Boating, Pool
- **Science**: Tech (Smart Home, Homelab), Telescopes, Weather

## Technical Stack

Built with [Hugo](https://gohugo.io/) static site generator using Google's [Docsy](https://www.docsy.dev/) documentation theme.

## Contributing

Everyone is welcome to contribute! All content is written in Markdown - no web development experience necessary.

### How to Contribute

1. For edits to existing pages: Submit a PR to the current branch
2. For new pages/sections: Create a feature branch and submit a PR
3. Place all content in the appropriate category within `/content/en/docs/`
4. Follow the best practice: Create a folder for your section with an `_index.md` file
5. Store images in the same directory for easy reference
6. Include proper front matter in all Markdown files

### Repo Layout

- `main` - Primary development branch
- `gh-pages` - Deployed site (auto-generated)
- Feature branches - Named as `claude/*` for automated contributions

## Local Development

### Prerequisites
- Hugo Extended (v0.75.0+)
- Go (v1.19+)
- Node.js and npm

### Quick Start

```bash
# Install dependencies
npm install

# Run local server
hugo server

# Or use Docker
docker-compose up
```

The site will be available at `http://localhost:1313`

## Deployment

The site deploys automatically via:
- **GitHub Actions** → GitHub Pages
- **Netlify** (alternative deployment)

## License

Copyright © Meaty Media
