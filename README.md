git clone https://github.com/anczzwx/css-fundamentals-lab.git
git add .
git commit -m "init project "
git push
git add index.html
git commit -m "create main page"
git checkout -b feature/css
git commit -m “add basic CSS selectors"
git add css/styles.css
git commit -m "add  box model styles"
git add css/styles.css
git commit -m "add flexbox layouts"
git checkout main
git merge feature/main
git merge feature/css
git push origin development
git push origin main