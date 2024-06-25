[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15328131&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - Step 1: Visit the Official Website of the Visual Studio Code using any web browser like Google Chrome, Microsoft Edge, etc. Click on https://code.visualstudio.com/Download
Step 2: Press the “Download for Windows” button on the website to start the download of the Visual Studio Code Application.
Step 3: When the download finishes, then the Visual Studio Code Icon appears in the downloads folder.
Step 4: Click on the Installer icon to start the installation process of the Visual Studio Code.
Step 5: After the Installer opens, it will ask you to accept the terms and conditions of the Visual Studio Code. Click on I accept the agreement and then click the Next button.
Step 6: Choose the location data for running the Visual Studio Code. It will then ask you to browse the location. Then click on the Next button.
Step 7: Then it will ask to begin the installation setup. Click on the Install button.
Step 8: After clicking on Install, it will take about 1 minute to install the Visual Studio Code on your device.
Step 9: After the Installation setup for Visual Studio Code is finished, it will show a window like this below. Tick the “Launch Visual Studio Code” checkbox and then click Next.
Step 10: After the previous step, the Visual Studio Code window opens successfully. Now you can create a new file in the Visual Studio Code window and choose a language of yours.
Reference: https://code.visualstudio.com/docs/setup/windows


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
VS Code provides different scopes for settings:
1)	User settings - Settings that apply globally to any instance of VS Code you open.
2)	Workspace settings - Settings stored inside your workspace and only apply when the workspace is opened.
Use the Settings editor to review and change VS Code settings. To open the Settings editor, navigate to File > Preferences > Settings. Alternately, open the Settings editor from the Command Palette (Ctrl+Shift+P) with Preferences: Open Settings or use the keyboard shortcut (Ctrl+,). Changes to settings are applied directly by VS Code, as you change them. Modified settings are indicated with a blue line, similar to modified lines in the editor. Each setting can be edited by either a checkbox, a text input field, or a dropdown. Edit the text or select the option you want to change to the desired settings. Settings are represented in groups, so that you can navigate to them easily. There is a Commonly Used group at the top, which shows popular customizations. The Settings editor search bar has several filters to make it easier to manage your settings. To the right of the search bar is a filter button with a funnel icon that provides options to easily add a filter to the search bar. To check which settings you have configured, there is a @modified filter in the search bar. A setting shows up under this filter if its value differs from the default value, or if its value is explicitly set in the respective settings JSON file. This filter can be useful if you have forgotten whether you configured a setting, or if the editor is not behaving as you expect because you accidentally configured a setting. There are several other handy filters to help with searching through settings. Type the @ symbol in the search bar to discover the different filters. The filters that are available are:
@ext - Settings specific to an extension. You provide the extension ID such as @ext:ms-python.python.
@feature - Settings specific to a Features subgroup. For example, @feature:explorer shows settings of the File Explorer.
@id - Find a setting based on the setting ID. For example, @id:workbench.activityBar.visible.
@lang - Apply a language filter based on a language ID. For example, @lang:typescript. See Language-specific editor settings for more details.
@tag - Settings specific to a system of VS Code. For example, @tag:workspaceTrust for settings related to Workspace Trust, or @tag:accessibility for settings related to accessibility.
The search bar remembers your settings search queries and supports Undo/Redo (Ctrl+Z/Ctrl+Y). You can quickly clear a search term or filter with the Clear Settings Search Input button at the right of the search bar. Installed VS Code extensions can also contribute their own settings, which you can review under the Extensions section of the Settings editor. Workspace settings are specific to a project and can be shared across developers on a project. Workspace settings override user settings. Configurations can be overridden at multiple levels by the different setting scopes. In the following list, later scopes override earlier scopes:
•	Default settings - This scope represents the default unconfigured setting values.
•	User settings - Apply globally to all VS Code instances.
•	Remote settings - Apply to a remote machine opened by a user.
•	Workspace settings - Apply to the open folder or workspace.
•	Workspace Folder settings - Apply to a specific folder of a multi-root workspace.
•	Language-specific default settings - These are language-specific default values that can be contributed by extensions.
•	Language-specific user settings - Same as User settings, but specific to a language.
•	Language-specific remote settings - Same as Remote settings, but specific to a language.
•	Language-specific workspace settings - Same as Workspace settings, but specific to a language.
•	Language-specific workspace folder settings - Same as Workspace Folder settings, but specific to a language.
•	Policy settings - Set by the system administrator, these values always override other setting values.
Reference: https://code.visualstudio.com/docs/getstarted/settings

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   - VS Code comes with a simple and intuitive layout that maximizes the space provided for the editor, while leaving ample room to browse and access the full context of your folder or project. The user interface is divided into five main areas:
•	Editor - The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.
•	Primary Side Bar - Contains different views like the Explorer to assist you while working on your project.
•	Status Bar - Information about the opened project and the files you edit.
•	Activity Bar - Located on the far left-hand side. It lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.
•	Panel - An additional space for views below the editor region. By default, it contains output, debug information, errors and warnings, and an integrated terminal. The Panel can also be moved to the left or right for more vertical space.
Reference: https://code.visualstudio.com/docs/getstarted/userinterface


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
The Command Palette provides access to many commands. You can run editor commands, open files, search for symbols, and see a quick outline of a file, all using the same interactive window. It can be accessed on VS Code using the command Ctrl+Shift+P. This brings up the Command Palette.
 Reference: https://code.visualstudio.com/docs/getstarted/userinterface

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow. VS Code's rich extensibility model lets extension authors plug directly into the VS Code UI and contribute functionality through the same APIs used by VS Code.
•	You can browse and install extensions from within VS Code. Bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X).
•	To install an extension, select the Install button. Once the installation is complete, the Install button will change to the Manage gear button.
•	VS Code makes it easy to manage your extensions. You can install, disable, update, and uninstall extensions through the Extensions view, the Command Palette.
Examples of VS Code extensions essential for web development are:
1.	Prettier 
2.	JavaScript Booster
3.	ESLint
4.	GitLens
5.	Live Server
6.	CSS Peek
7.	IntelliCode
8.	VSCode Icons
Reference: https://code.visualstudio.com/docs/editor/extension-marketplace

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
To open a terminal as follows:
•	From the menu, use the Terminal > New Terminal or View > Terminal menu commands.
•	From the Command Palette (Ctrl+Shift+P), use the View: Toggle Terminal command.
•	In the Explorer, you can use the Open in Integrated Terminal context menu command to open a new terminal from a folder.
•	To toggle the terminal panel, use the Ctrl+` keyboard shortcut.
•	To create a new terminal, use the Ctrl+Shift+` keyboard shortcut.
One of the key advantages of VS Code's integrated terminal is its seamless integration with Git commands and version control operations. The integration eliminates the need to switch between different applications or command-line interfaces, allowing for a more cohesive and productive development process.
References: https://code.visualstudio.com/docs/terminal/basics 
          https://www.youngwonks.com/blog/how-to-open-terminal-in-visual-studio-code

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
a)	To create files and folders on VS Code: 
Press ctrl+shift+p to open command panel and type Create File or Create Folder.
b)	To manage files and folders on VS Code:
Press Ctrl–Shift–F (Windows) or choose Edit > Find in Files.
Users can efficiently navigate between different files and directories on folders by doing the following:
Hold Ctrl and press Tab to view a list of all files open in an editor group. To open one of these files, use Tab again to pick the file you want to navigate to, then release Ctrl to open it. Alternatively, you can use Alt+Left and Alt+Right to navigate between files and edit locations. If you are jumping around between different lines of the same file, these shortcuts allow you to navigate between those locations easily.
References: https://github.com/ritwickdey/vscode-create-file-folder
      https://www.nobledesktop.com/learn/visual-studio-code/topic-2a-vs-code-working-with-folders-files-the-sidebar
https://code.visualstudio.com/docs/editor/editingevolved

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
Users and find and customize settings in VS Code by doing the following:
Use the Settings editor to review and change VS Code settings. To open the Settings editor, navigate to File > Preferences > Settings. Alternately, open the Settings editor from the Command Palette (Ctrl+Shift+P) with Preferences: Open Settings or use the keyboard shortcut (Ctrl+,). 
How to change font size on VS Code:
Open the settings (File > Preferences > Settings) or use the keyboard shortcut (Ctrl +,) Then type “font size” in the search box.
How to change theme on VS Code:
•	Select the File > Preferences > Theme > Color Theme menu item, or use the Preferences: Color Theme command (Ctrl+K Ctrl+T) to display the Color Theme picker.
•	Use the Up and Down keys to navigate through the list and preview the colors of the theme.
•	Select the theme you want and press Enter.
How to change key bindings on VS Code: 
Right-click on any action item in your workbench, and select Customize Keybinding. If the action has a when clause, it's automatically included, making it easier to set up your keybindings just the way you need them. 
References: https://code.visualstudio.com/docs/getstarted/settings
          https://code.visualstudio.com/docs/getstarted/themes
          https://code.visualstudio.com/docs/getstarted/keybindings

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Steps to set up debugging in VS Code:
To bring up the Run and Debug view, select the Run and Debug icon in the Activity Bar on the side of VS Code. You can also use the keyboard shortcut Ctrl+Shift+D.
Steps to start debugging a simple program in VS Code:
To run or debug a simple app in VS Code, select Run and Debug on the Debug start view or press F5 and VS Code will try to run your currently active file.
References: https://code.visualstudio.com/docs/editor/debugging

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Steps to integrate Git with VS Code for version control are as follows:
Step 1: Open Terminal in VS Code by using the shortcut key Ctrl+~. Here you will see that currently, it has PowerShell and we have to add bash to it.
Step 2: Then, you have to open settings by File->Preferences->Settings or by pressing Ctrl+,. You have to click on the Open Settings (JSON) icon.
Step 3: On clicking, you will see the settings page. You have to add the below properties at the last of all settings:
"terminal. integrated. profiles.windows":{"Git Bash":{"path":"C:\\Program Files\\Git\\bin\\bash.exe"}, },
"terminal.integrated.defaultProfile.windows": "Git Bash"
Step 4: And that’s all when you will reopen VS Code then you will see that Git Bash has been integrated. Now you can run Git Bash commands directly in VS Code.
To initialize a Git repository:
•	Open Git Bash.
•	Navigate to the root directory of your project.
•	Initialize the local directory as a Git repository. By default, the initial branch is called main.
•	If you’re using Git 2.28.0 or a later version, you can set the name of the default branch using -b.
        git init -b main.
To make commits, enter the command:
git commit -m "First commit"
	To push changes to GitHub, enter the command git push origin main. If your default branch is not named "main," replace "main" with the name of your default branch.
References: https://www.geeksforgeeks.org/how-to-integrate-git-bash-with-visual-studio-code/
          https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

