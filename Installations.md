### Summary
1. **Git:** Download from the Git website, run the installer, follow the defaults, and verify with `git --version`.

2. **NVM:** Download from the GitHub releases page, run the installer, configure with `nvm install latest` and `nvm use`, and verify with `node -v`.

3. **VSCode:** Download from the VSCode website, run the installer, and install recommended extensions.

4. **ResponsivelyApp:** Download from the ResponsivelyApp website, run the installer, and verify by opening the app.

### 1. Installing Git
	1. **Download Git:**
		Go to the [Git website](https://git-scm.com/).
   
	2. **Download Git:**
		Locate the downloaded .exe file and run it.
		Follow the installation wizard. You can mostly use the default settings, but pay attention to the following options:
		
		1. Select Components: Make sure "Git Bash Here" and "Git GUI Here" are checked.
		2. Adjusting your PATH environment: Choose "Git from the command line and also from 3rd-party software".
		3. Configuring the line ending conversions: Choose "Checkout Windows-style, commit Unix-style line endings".
		
	3. **Finish Installation:**
		Click "Next" through the remaining steps and then "Finish".
		
	4. **Verify Installation:**
		Open Command Prompt or PowerShell.
		Type git --version to check if Git is installed correctly.
	
	
### 2. Installing Node Version Manager (NVM)
	1. **Download NVM for Windows:**
		Go to the [NVM for Windows GitHub releases page](https://github.com/coreybutler/nvm-windows/releases).

	2. **Run the Installer:**
		Extract the contents of the zip file.
		Run nvm-setup.exe and follow the installation wizard.
	
	3. **Configure NVM:**
		Open Command Prompt or PowerShell.
		Type nvm -v to verify the installation.
	
	4. **Install the latest version of Node.js** 
		Type: nvm install latest.
		
	5. **Use the installed version** 
		Type: nvm use <version-number>.
		
	6. **Verify Installation:**
		Type node -v and npm -v to ensure Node.js and npm are installed.
		
### 3. Installing Visual Studio Code (VSCode)
	1. **Download VSCode:**
		Go to the [VSCode website](https://code.visualstudio.com/).
		
	2. **Run the Installer:**
		Locate the downloaded .exe file and run it.
		Follow the installation wizard. You can use the default settings.
		
	3. **Install Extensions:**
		Open VSCode.
		Go to the Extensions view by clicking on the square icon in the sidebar or pressing Ctrl+Shift+X.
		Search for and install the following extensions:
			"ESLint"
			"Prettier - Code formatter"
			"GitLens — Git supercharged"
			
### 4. Installing ResponsivelyApp
	1. **Download ResponsivelyApp:**
		Go to the [ResponsivelyApp website](https://responsively.app/).
		
	2. **Run the Installer:**
		Locate the downloaded .exe file and run it.
		Follow the installation wizard.
	
	3. **Verify Installation:**
		Open ResponsivelyApp to ensure it runs correctly.
