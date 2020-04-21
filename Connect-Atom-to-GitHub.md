# Connect Atom and Github- a step-by-step guide

Create a new repository 'username/repository-name' (e.g., luenhchang/PhD_polygenic_risk_score_analysis) in GitHub

Create a new folder in a local computer (e.g., `D:\git\PhD-polygenic-risk-score-analysis`)

Copy the [link of the repo](https://github.com/luenhchang/PhD_polygenic_risk_score_analysis.git)
![](https://i.imgur.com/DbJWx80.png)


In Atom, bring up Command Palette in ATOM by  Ctrl+Shift+p and select `GitHub:Clone` [git-clone atom editor plugin](https://atom.io/packages/git-clone)

Add the repo link to **Clone from**

Add the folder link to **To directory** Keep this folder as empty until the Atom-Gitgun link is established.
![Git:Clone, outdated example](https://i.imgur.com/dHPcIKJ.png)

Hit Clone. This creates a `.git` folder in the local folder.

Right-click the folder> New File> Add a new file testing_git.py to the folder. The local folder and the newly added file are shown in green, indicating they are recognised by Atom as a GitHub repository

![recognised as a GitHub repository](https://i.imgur.com/PiiUzAn.png)

If your project panel is not shown up on the left sidebar, it maybe disabled by installed package [Toggle tree view](https://discuss.atom.io/t/how-to-reopen-the-sidebar-on-atom-sorry-for-stupid-question/15524/4)

Go to [GitHub for Atom login](https://github.atom.io/login). Log into GitHub and copy the token

In Atom, hit the GitHub icon. Paste the token. Note firewall (e.g., QIMR staff network) can block the authentication and give an error of `Failed to fetch`

![](https://i.imgur.com/K1cukw4.png)

Change the file testing_git.py and save it

Hit the 'Git' icon. You will see this file under 'Unstaged Changes' tab. Use the dropdown list to make sure the correct repository is selected.

Hit 'Stage All'

Enter text in the commit message box. The text reveals the main change or task (e.g. Testing Git)

Hit 'Commit to master' tab

Hit 'Push' tab. This tab will show 'Pushing', meaning the testing file is being pushed to the github repository

Check the files that have been pushed to the [repo](https://github.com/luenhchang/PhD_polygenic_risk_score_analysis). You should see 2 files there- README.md, testing_git.py

Add a new folder of files to the main folder and repeat the steps (1) Stage All type (2)'Adding references folder' to commit message box (3) commit to master (4) Push

Add another new folder using the same approach

reference: [How to connect Github with Atom - Easiest Way!](https://www.youtube.com/watch?v=6HsZMl-qV5k&t=317s)
