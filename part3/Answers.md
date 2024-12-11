# Part 3: Git Manual
Imagine you are working at a game studio, and they want you to help with installing Git. 

1. Write instructions on installing git on a windows system. Making sure to include

    a. What are the requirements to install Git on a system.
    ## anwser p3 q1a

    ```
    ... - Operating system Windows 7 or later
        - Disk at least 200mb for installation
        - Memory Depends on what you are up loading 8GB is a good number for git
        - Admin Privileges, you need admin privileges to install git

    ```

    b. If you had issues installing Git the workplace, give instructions on who you could you enquire about the installation disruption.
    ## anwser p3 q1b

    ```
    ... 1. visit [Git](https://git-scm.com/) and download the latest version for windows
        2. download the installer (git-.exe)
        3. follow installation wizard instructions:
         - Choose the installation directory.
         - Select components to install (leave default for most users).
         - Choose the default editor used by Git (e.g., Nano, Vim, Visual Studio Code).
         - Select appropriate line-ending conversion settings (default is recommended).
         - Choose the terminal emulator to use with Git (default is recommended).
         - Enable options to add Git to the PATH environment and allow Git Credential Manager installation.
        4. complete installing
        5. Verify the installation by opening a command prompt and typing: bash git --version

    ```

2. Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git.

    a. List the most important principles/techniques for creating and working with repositories
    ## anwser p3 q2a

    ```
    ... - Choose the Right Version Control system
        - create proper repository names
        - use .gitignore files
	    - commit often on small thing rather than large
	    - make sure main branch is stable
	    - use tags for version control
	    - keep Repository clean and organized
	    - collaborate using issues
	    - have documentation and readme's
	    - use code review
	    - use permisions to control who can view and write
	    - handle Merge Conflicts when they happen
	    - regularly Sync forks
	    - never commit sensitive information
	    - regularly backup your repository
	    - regularly do 

    ```

    b. List the most important principles/techniques for creating and working with branches
    
    ## anwser p3 q2b
    ```
    ... -Make a clear Branching Model like Main/Stagin/Development
	    -Branches names should be clear
	    -use pull request for merging
	    -commit small logical changes
	    -Test before merging
	    -resolve conflicts early
    ```

3. List the steps in a Git workflow that the team should follow when working on projects.
    ## anwser p3 q3

    ```
    ... -List the steps in a Git workflow that the team should follow when working on projects.
        -Git Workflow Steps for Team Collaboration:

        -1. Set Up the Repository

        -Initialize the repository or clone an existing one.
        -Ensure all team members have access and the repository is set up with a clear structure.

        -2. Create Staging and Development Branches

        -Create two main working branches:
        -Development: For ongoing feature development.
        -Staging: For testing and final preparation before merging to the main branch.

        -3. Fork the Repository

        -Each team member forks the repository to their account for independent work.

        -4. Commit Changes to the Development Branch

        -Work on your features or fixes in a new branch off Development (e.g., feature/feature-name or bugfix/issue-name).
        -Commit changes frequently with clear and descriptive messages.

        -5. Merge Forked Development Branch into Regular Development Branch

        -Open a pull request from your forked repository back into the Development branch of the main repository.
        -Perform a code review and resolve conflicts if necessary before merging.

        -6. Merge Development into Staging

        -Once features are complete and tested in Development, merge the Development branch into Staging for final testing.

        -7. Test Changes Locally

        -Run tests locally to verify that changes on the Staging branch work as expected and do not introduce new issues.

        -8. Merge Staging into Main

        -After successful testing, merge the Staging branch into the Main branch for deployment or release.
    ```