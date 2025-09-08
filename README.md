# STLab

08-09-2025

# 1. Cloning
PS C:\Users\abhin> git clone https://github.com/Abhinav-Jain252/STLab.git<br/>
Cloning into 'STLab'...<br/>
warning: You appear to have cloned an empty repository.<br/>

# 2. Shifting to STLab
PS C:\Users\abhin> cd STLab<br/>
PS C:\Users\abhin\STLab> git status<br/>
On branch main<br/>

No commits yet<br/>

nothing to commit (create/copy files and use "git add" to track)<br/>


# 3. Git Config
PS C:\Users\abhin\STLab> git config --global user.name "Abhinav-Jain252"<br/>
PS C:\Users\abhin\STLab> git config --global --list<br/>
core.editor="C:\Users\abhin\AppData\Local\Programs\Microsoft VS Code\bin\code" --<br/>
user.name=Abhinav-Jain252<br/>
PS C:\Users\abhin\STLab> git config --global user.email "jainabhinav478@gmail.com"   <br/>
PS C:\Users\abhin\STLab> git config --global --list<br/>
core.editor="C:\Users\abhin\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait<br/>
user.name=Abhinav-Jain252<br/>
user.email=jainabhinav478@gmail.com<br/>


# 4. Add, Commit and push
PS C:\Users\abhin\OneDrive\Desktop\Abhinav Jain\IIT JAMMU\First Sem\Software Tools\Git\STLab> git add .<br/>
PS C:\Users\abhin\OneDrive\Desktop\Abhinav Jain\IIT JAMMU\First Sem\Software Tools\Git\STLab> git commit -m "Added break with every line"<br/>
[main ba6b281] Added break with every line<br/>
 1 file changed, 17 insertions(+), 17 deletions(-)<br/>
PS C:\Users\abhin\OneDrive\Desktop\Abhinav Jain\IIT JAMMU\First Sem\Software Tools\Git\STLab> git status<br/>
On branch main<br/>
Your branch is ahead of 'origin/main' by 1 commit.<br/>
  (use "git push" to publish your local commits)<br/>

nothing to commit, working tree clean<br/>
PS C:\Users\abhin\OneDrive\Desktop\Abhinav Jain\IIT JAMMU\First Sem\Software <br/>Tools\Git\STLab> git push origin main<br/>
info: please complete authentication in your browser...<br/>
Enumerating objects: 5, done.<br/>
Counting objects: 100% (5/5), done.<br/>
Delta compression using up to 8 threads<br/>
Compressing objects: 100% (2/2), done.<br/>
Writing objects: 100% (3/3), 404 bytes | 202.00 KiB/s, done.<br/>
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)<br/>
remote: Resolving deltas: 100% (1/1), completed with 1 local object.<br/>
To https://github.com/Abhinav-Jain252/STLab.git<br/>
   27887ce..ba6b281  main -> main<br/>