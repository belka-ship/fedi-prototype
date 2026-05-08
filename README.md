# Fedi First-Run Redesign Prototype

A 5-day-shippable redesign of the first-run + community-choice flow for Fedi.

## Overview

This prototype showcases a redesigned onboarding experience for Fedi, focusing on:
- **Simplified Introduction**: Clear, step-by-step explanation of how Fedi works
- **Community Discovery**: Easy-to-browse community selection with smart recommendations
- **Detailed Community Views**: Comprehensive information about each community
- **Modern UI**: Beautiful, mobile-first design with smooth animations

## Features

### 📱 Mobile-First Design
- Phone frame simulation for realistic mobile experience
- Responsive layout optimized for mobile devices
- Touch-friendly interactions

### 🎨 Beautiful UI/UX
- Modern gradient backgrounds
- Smooth animations and transitions
- Clear typography hierarchy
- Intuitive navigation patterns

### 👥 Community Features
- Pre-configured communities with realistic data
- Guardian information and verification status
- Available community modules/apps
- Regional and language filtering

### ⚡ Interactive Elements
- Step-by-step onboarding carousel
- Filterable community list
- Detailed community information pages
- Post-join homescreen experience

## Getting Started

### Prerequisites
- Node.js 16+ 
- A modern web browser

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/fedi-prototype.git
cd fedi-prototype
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

### Quick Start (No Installation)

If you just want to view the prototype without installing dependencies:

1. Open `fedi-prototype_1.jsx` in a code editor
2. Use a React playground or local development server to run the component

## Project Structure

```
fedi-prototype/
├── fedi-prototype_1.jsx    # Main React component
├── package.json           # Project dependencies
└── README.md             # This file
```

## Key Components

- **PhoneFrame**: Mobile device wrapper with realistic styling
- **IntroCarousel**: 3-step onboarding introduction
- **CommunityList**: Browseable community selection
- **CommunityDetail**: Detailed community information
- **Homescreen**: Post-join wallet interface

## Technologies Used

- **React 18**: Component framework
- **Lucide React**: Icon library
- **Tailwind CSS**: Utility-first styling (via CDN in prototype)

## Community Data

The prototype includes 5 sample communities:
- Global Bitcoin Federation
- Victoria BTC  
- Orange Club Africa
- LatNet
- Marigold Trust Network

Each community includes realistic data about:
- Member counts and regions
- Guardian verification status
- Available modules/apps
- Community focus and use cases

## Contributing

This is a prototype for demonstration purposes. For the actual Fedi project, please refer to the main Fedi repository.

## License

MIT License - see LICENSE file for details

---

**Note**: This is a design prototype created for internal review and testing. The community data and guardian information are fictional and for demonstration purposes only.
