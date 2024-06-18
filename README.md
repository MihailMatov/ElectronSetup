# ElectronSetup

## Prerequisites

- **Node.js**: Ensure you have Node.js installed. 
- **Git Bash**: Install Git Bash.

## Setup Instructions

1. **Clone the Repository**:
2. **Open the Folder with Visual Studio**:
     Open the cloned repository folder in Visual Studio.

3. **Install Dependencies**:
     npm ci

5. **Create Windows Installer**:
     npx gulp create-windows-installer

## Development

- **Compile Changes**:
    After making changes, run the following command to compile:
    npm run compile

    You will find your files and the compiled executable for Windows in `dist/my-electron-app-win32-x64`.

- **Run in Development Mode**:
    To see changes in real-time, run:
    npm start
