add publication
 * hugo new --kind publication publication/thiessen2021active
 * fill in details

test: 
hugo server

deploy:
git add .
git commit -m "new pub"
git push