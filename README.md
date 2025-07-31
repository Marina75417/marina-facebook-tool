# Initialize repo
git clone https://github.com/marina75417/marina-facebook-tool
cd marina-facebook-tool

# Add files
echo "# MARINA KHAN - Facebook Reporting Tool" > README.md
echo "APP_ID=your_id_here" > .env  # Add to .gitignore!
git add marina_khan_facebook_tool.py README.md

# Commit & push
git commit -m "Official MARINA KHAN Facebook Tool"
git remote add origin https://github.com/marina75417/marina-facebook-tool.git
git push -u origin main
