# Penetration Testing Simulation

![Penetration Testing](https://img.shields.io/badge/Security-Penetration%20Testing-red)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0.2-blue)
![License](https://img.shields.io/badge/License-MIT-green)

An interactive web-based simulation of a complete penetration testing workflow, designed for educational purposes. This application walks users through the five key phases of penetration testing against a vulnerable machine, demonstrating commands, outputs, and explaining techniques.

## 🔗 Live Demo

[Access the live simulation](https://xlxawphr.manus.space)

![Penetration Testing Simulation Screenshot](https://via.placeholder.com/800x450.png?text=Penetration+Testing+Simulation)

## 🎯 Project Overview

This project simulates a penetration test against the "Basic Pentesting 1" vulnerable machine, guiding users through:

1. **Reconnaissance** - Discovering target systems on a network
2. **Scanning** - Identifying open ports and services
3. **Enumeration** - Gathering detailed information about target services
4. **Exploitation** - Leveraging vulnerabilities to gain access
5. **Privilege Escalation** - Elevating permissions to gain full control

The simulation provides realistic terminal outputs, detailed explanations, and key learning points for each step, making it an ideal educational tool for cybersecurity students and professionals.

## ✨ Features

- **Interactive Terminal Simulation**: Realistic command and output displays
- **Step-by-Step Guidance**: Navigate through each phase of penetration testing
- **Educational Content**: Detailed explanations and learning points for each command
- **Progress Tracking**: Visual indication of progress through the penetration testing workflow
- **Auto-Play Mode**: Option for automated progression through the simulation
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Technologies Used

- **React**: Frontend library for building the user interface
- **TypeScript**: Type-safe JavaScript for improved development experience
- **Vite**: Next-generation frontend tooling for faster development
- **CSS**: Styling with modern CSS techniques

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or pnpm package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pentest-simulation.git
   cd pentest-simulation
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Start the development server:
   ```bash
   pnpm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
pnpm run build
```

The built files will be in the `dist` directory, ready to be deployed to any static hosting service.

## 📚 Educational Purpose

This simulation is designed for educational purposes only. It demonstrates:

- Common penetration testing methodologies
- Tools used in ethical hacking (Nmap, enum4linux, Hydra, etc.)
- Vulnerability identification and exploitation techniques
- Privilege escalation methods
- Documentation practices for security professionals

## 🔒 Security Notice

The techniques demonstrated in this simulation should only be used:

- In controlled, authorized environments
- With proper permission
- For educational or professional security assessment purposes

Unauthorized penetration testing is illegal and unethical.

## 📋 Project Structure

```
src/
├── components/
│   ├── PentestSimulation.tsx  # Main simulation component
│   └── ui/                    # UI components
├── App.tsx                    # Main application component
├── main.tsx                   # Application entry point
└── index.css                  # Global styles
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Based on the "Basic Pentesting 1" vulnerable VM by Josiah Pierce
- Inspired by real-world penetration testing methodologies
- Created for educational purposes to help security enthusiasts learn penetration testing concepts
