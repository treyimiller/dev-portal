 ____  ____  _  _   ___  __    ___  ____  __ _  ____ 
(    \(  __)/ )( \ / __)/  \  / __)(  __)(  ( \(_  _)
 ) D ( ) _) \ \/ /( (__(  O )( (_ \ ) _) /    /  )(  
(____/(____) \__/  \___)\__/  \___/(____)\_)__) (__) 

README

React baseplate for Devcogent Platforms

## Stack

- **React** with TypeScript
- **Tailwind CSS** for styling
- **React Router DOM** for navigation
- **HTML** entry point for DOM mounting

## Structure

```
├── public/
│   └── index.html
├── src/
│   ├── main.tsx          # React entry point
│   ├── App.tsx           # Route container
│   ├── index.css         # Tailwind and component styles
│   └── pages/            # Modular pages (Home, SignIn, etc)
├── tailwind.config.js    # Custom colors and theme
├── package.json          # Scripts and dependencies
├── LICENSE               # Client-only license
└── README.md             # You're here
```

Licensed Use

1. Clone the repository
```bash
git clone https://github.com/devcogent/client-portal-template.git
cd client-portal-template
```

2. Install dependencies
```bash
npm install
```

3. Run the development server
```bash
npm run dev
```

4. Visit [http://localhost:5173](http://localhost:5173)

Page modification within 'src/pages/'
API integrations within 'src/lib/'