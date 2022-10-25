Important things to do before starting anything
1. Activate any virtual environment you would need to run programs
    ->source <location of your virtual environment>/Scripts/activate ***for Windows
    ->->source <location of your virtual environment>/Scripts/activate ***for Linux
2. Pull repositories
    Case 1: If you have an SSH-config file, you would be able to ->git pull without anty connection issues.
    Case 2: You DO NOT have an SSH-config file 
        a. Call the agent -> eval "$(ssh-agent -s)"
        b. Tell the agent where and which PRIVATE KEY you are using -> ssh-add ~/.ssh/<your PRIVATE KEY name>
        c. Pull the repository(-ies) -> git pull