[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15255716&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   ---
   ### Steps required to install VS-code on windows
    #### 1. Download the Visual Studio Code installer for Windows.
    #### 2. Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). 3. 3. This will only take a minute.
#### By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.
## Alternatively

### Windows Subsystem for Linux
Windows is a popular operating system and it can be a great cross-platform development environment. This section describes cross-platform features such as the Windows Subsystem for Linux (WSL) and the new Windows Terminal.

### Recent Windows build
&nbsp;&nbsp;Make sure you are on a recent Windows 11 build. Check Settings > Windows Update to see if you are up-to-date.

&nbsp;&nbsp;Windows as a developer machine
&nbsp;&nbsp;With WSL, you can install and run Linux distributions on Windows. This enables you to develop and test your source code on Linux while still working locally on your Windows machine.

&nbsp;&nbsp;When coupled with the WSL extension, you get full VS Code editing and debugging support while running in the context of WSL.

---
2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   ### 1. Basic Settings Configuration
### a. User Interface and Appearance
#### Theme: Choose a theme that is comfortable for your eyes.
Dark Theme: "One Dark Pro" or "Dracula"
Light Theme: "Atom One Light" or "Quiet Light"
Icon Theme: "Material Icon Theme" for better visual file distinctions.
b. Editor Settings
Font Family: Set to a clear, legible monospace font like "Fira Code" or "Cascadia Code".
Font Size: Adjust to your preference, typically between 12-14px.

Word Wrap: Enable word wrap to prevent horizontal scrolling.

Auto Save: Set to automatically save files after a delay.

#### 2. Extensions to Install
### a. General Enhancements
Settings Sync: Sync your settings, snippets, themes, and extensions across multiple devices.

Prettier - Code Formatter: Ensure consistent code formatting.


ESLint: Integrate ESLint for JavaScript/TypeScript projects for linting.

b. Language-Specific Extensions
Python: "Python" by Microsoft for Python development.
JavaScript/TypeScript: "ESLint" and "Prettier".
HTML/CSS: "HTML CSS Support" for better autocompletion and linting.
C/C++: "C/C++" by Microsoft for debugging and IntelliSense.
### 3. Debugging Configuration
#### a. Common Debugging Tools

#### Live Server: Launch a development local server with live reload feature.
### 4. Source 
### Control Integration
#### a. Git Integration
#### GitLens: Enhance Git capabilities within VS Code, making it easier to visualize code authorship and history.
#### Git Graph: Provides a graph to visualize the repository's commit history.

### 5. Keybindings
#### Customize keybindings to enhance productivity. For example, set up shortcuts for common tasks like duplicating lines, opening the integrated terminal, or running code snippets.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   #### 1._Activity Bar_ - Located on the far left-hand side. Lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.

   #### 2._Side Bar_ -  Contains different views like the Explorer to assist you while working on your project.

   #### 3._Editor Group_ - When you split an editor (using the Split Editor or Open to the Side commands), a new editor region (edit group) is created which can hold a group of items. You can open as many editor groups as you like side by side vertically and horizontally.

   #### 4. _Status Bar._ -  Information about the opened project and the files you edit.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   #### The most important key combination to know is Ctrl+Shift+P, which  up the Command Palette. From here, you have access to all functionality within VS Code, including keyboard shortcuts for the most common operations.

   Examples of common tasks performed using commmand palette
   #### Accessing various keyboard shortcuts
   #### Creating projects eg flutter
   #### Accessing various settings and configurations.
   #### Changing themes and font
   #### Accessing editor commands,open files, search for symbols, and see a quick outline of a file
   #### You can install, disable, update, and uninstall extensions



5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   #### Extensions help you add languages, debuggers, and tools to your installation to support your development workflow

   #### Users can bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X).

   Common Extensions
   General Extensions
Prettier - Code Formatter
Ensures consistent code formatting across your project.

ESLint
Integrates ESLint into VS Code for JavaScript/TypeScript linting.

Live Server
Launches a local development server with live reload feature for static and dynamic pages.

Path Intellisense
Autocompletes file paths in your projects.

HTML CSS Support
Enhances HTML and CSS development with better autocompletion.

JavaScript (ES6) Code Snippets
Provides a collection of ES6 code snippets for faster development.

CSS Peek
Allows you to quickly peek and jump to CSS definitions from your HTML files.

IntelliSense for CSS class names in HTML
Autocompletes CSS class names in HTML files.

Debugger for Chrome
Debug your JavaScript code in Google Chrome directly from VS Code.

npm Intellisense
Autocompletes npm modules in import statements.

Auto Rename Tag
Automatically renames paired HTML/XML tags.

Bracket Pair Colorizer
Colors matching brackets to make nested code blocks more readable.

GitLens
Enhances Git capabilities, making it easier to visualize code authorship, history, and repository changes.

REST Client
Allows you to send HTTP requests and view responses directly in VS Code.

CSS and Styling Extensions
Tailwind CSS IntelliSense
Provides autocomplete, syntax highlighting, and linting for Tailwind CSS classes.

Emmet
Provides high-speed coding and editing for HTML, CSS, and more.

#### Prettify JSON
Formats your JSON files for better readability.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   #### integrated terminal that starts at the root of your workspace. It provides integration with the editor to support features like links and error detection. The integrated terminal can run commands such as mkdir and git just like a standalone terminal.

   You can open a terminal as follows:

#### From the menu, use the Terminal > New Terminal or View > Terminal menu commands.
#### From the Command Palette (Ctrl+Shift+P), use the View: Toggle Terminal command.
#### In the Explorer, you can use the Open in Integrated Terminal context menu command to open a new terminal from a folder.
#### To toggle the terminal panel, use the Ctrl+` keyboard shortcut.
#### To create a new terminal, use the Ctrl+Shift+` keyboard shortcut.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

