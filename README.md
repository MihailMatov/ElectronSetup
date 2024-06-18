# ElectronSetup

## Prerequisites

- **Node.js**: Ensure you have Node.js installed.  ->    [Node.js](https://nodejs.org/en)
- **Git Bash**: Install Git Bash.   ->   [Git Bash](https://www.git-scm.com/downloads)

## Setup Instructions

1. **Clone the Repository**:
         `git clone https://github.com/MihailMatov/ElectronSetup.git`
   
3. **Open the Folder with Visual Studio**:
        Open the cloned repository folder in Visual Studio.

4. **Install Dependencies**:
        `npm ci`

## Development

- **Compile Changes**:
    After making changes, run the following command to compile:
    `npm run compile`

    You will find your files and the compiled executable for Windows in _dist/my-electron-app-win32-x64_.

- **Run in Development Mode**:
    To see changes in real-time, run:
    `npm start`
