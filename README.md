echo "# lifearcai-platform" >> README.md      # Creates a README file
git init                                      # Initializes a new Git repository
git add README.md                             # Stages the README file for commit
git commit -m "first commit"                  # Commits the file with a message
git branch -M main                            # Creates and switches to the main branch
git remote add origin https://github.com/lifearcai/lifearcai-platform.git  # Links local repo to GitHub
git push -u origin main                       # Pushes the commit to GitHub
