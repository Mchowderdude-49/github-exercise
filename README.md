# git-exercise
# Navigate to a folder where you keep projects
cd ~/projects          # or wherever you like

# Clone
git clone https://github.com/<you>/git-exercise.git
cd git-exercise

def hello():
    """Print a friendly greeting."""
    print("hello")

    git add demo.py
git commit -m "Add hello() function"
git push origin main   # or 'master' if your repo uses that branch name
