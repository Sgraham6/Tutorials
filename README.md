## How to load large file
### Installing LFS
https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage
### Steps in Terminal
1. Make local clone of repository with: git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
2. Change directory to that with: $ cd directory_name
3. Pull changes to it with: $ git pull
4. Locate the clone in finder, and put the files in there from desktop
5. Initialize LFS with: $ git lfs install
6. See unmodified / untracked files with: $ git status
7. Stage all changes with: $ git add .
8. Commit changes with: $ git commit -m "message"
9. Run: $ git push origin main




## Tutorials Link
https://skills.github.com

## New SSH
In terminal:
1. type: ssh-keygen -t ed25519 -C "srgraham1114@gmail.com"
2. Press Enter twice
3. type: eval "$(ssh-agent -s)"
4. type: cat ~/.ssh/id_ed25519.pub
5. Copy resulting string
6. Go to GitHub -> Settings -> SSH and GPG Keys
7. Create a new key, give it a title, and paste the string in "Key"
8. Click "Add SSH key" 
