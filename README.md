# dcode Theme
##  Steps to follow 
### Step 1: Clone the github Repository
  1. Open a terminal or command prompt
  2. Run the following command to clone the repository:
     ```{bash}
     git clone https://github.com/yihunzeleke/dcode-theme-positron-r.git
     ```
  3. Navigate into the cloned repository
   ```{bash}
     cd dcode-theme
   ```
### 2. Install dependencies
  1. The theme repository have dependencies listed in `package.json` file. Install them using `npm` (Node.js must ne installed on your system)
     ```{bash}
     npm install
     ```
### 3. Package the Theme into a `.vsix` File
  1. To create a `.vsix` file, you need to use the `vsce` (Visual Studio Code Extension) tool. Install it globally if you don't already have it.
     ```{bash}
     sudo npm install -g @vscode/vsce
     ```
  2. Package the theme into a `.vsix` file
     ```{bash}
     vsce package
     ```
     This will generate a `.vsix` file in the root of cloned repository (e.g. `dcode-theme-0.0.2.vsix`
### Step 4: Install the `.vsix` File in Positron IDE
  1. Copy the generated `.vsix` file to your desired location.
  2. Open Positron IDE.
  3. Go to extension manager (cmd + Shift + X) on Mac and (Ctrl + Shift + X ) on Windows.
  4. Looke for an option to install from `.vsix` file.
  5. Select the `.vsix` file you created and install it. 

## A colour theme for my positron ide channel, dcode.
I've created this theme which is based off the colours used on my YouTube channel, **dcode**.

You'll find greens, yellows, blues and a touch of *italic* text.

## Screenshot
![alt text](https://raw.githubusercontent.com/dcode-youtube/dcode-theme/master/screenshots/dcode-theme-screenshot-01.jpg "dcode Theme Screenshot")


**Enjoy!**
