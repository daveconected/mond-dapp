Initialize Git (if not done already)
git init

# Connect to your GitHub
git remote add origin https://github.com/daveconected/mond-dapp.git

# Push code
git add .
git commit -m "Initial Mond dApp commit"
git branch -M main
git push -u origin main
