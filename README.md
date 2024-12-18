# Secure Password Generator

A modern, secure password generator built with React and TypeScript. Features a clean, dark-themed UI with password strength analysis and customizable generation options.

![Password Generator Screenshot](./screenshot.png)

## Features

- 🔐 Secure random password generation using `crypto.getRandomValues()`
- 📊 Real-time password strength analysis
- 🎨 Modern dark theme UI
- ⚙️ Customizable password options:
  - Password length (4-32 characters)
  - Lowercase letters (a-z)
  - Uppercase letters (A-Z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*)
- 📋 One-click copy to clipboard
- 📱 Responsive design
- 🔄 Instant password regeneration

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- Vite
- React Icons

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
\```bash
git clone https://github.com/yourusername/secure-password-generator.git
\```

2. Navigate to the project directory:
\```bash
cd secure-password-generator
\```

3. Install dependencies:
\```bash
npm install
\```

4. Start the development server:
\```bash
npm run dev
\```

5. Open your browser and visit `http://localhost:5173`

## Building for Production

To create a production build:

\```bash
npm run build
\```

The built files will be in the `dist` directory.

## Project Structure

\```
src/
├── components/           # React components
│   ├── buttons/         # Button components
│   ├── indicators/      # Indicator components
│   └── options/         # Option components
├── hooks/               # Custom React hooks
├── utils/               # Utility functions
│   ├── password/        # Password-related utilities
│   └── validation/      # Validation utilities
├── constants/           # Constants and configuration
├── types/               # TypeScript type definitions
└── styles/              # CSS and style-related files
\```

## Security

This application uses the Web Crypto API's `crypto.getRandomValues()` for generating cryptographically secure random values. The password generation process follows security best practices to ensure generated passwords are truly random and secure.

## Contributing

1. Fork the repository
2. Create your feature branch (\`git checkout -b feature/AmazingFeature\`)
3. Commit your changes (\`git commit -m 'Add some AmazingFeature'\`)
4. Push to the branch (\`git push origin feature/AmazingFeature\`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React Icons](https://react-icons.github.io/react-icons/) for the beautiful icons
- [Tailwind CSS](https://tailwindcss.com/) for the styling system