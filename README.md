# daily-picks
# Today's Bet Options
git init
git checkout -b main
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/mofam619/daily-pick.git
# bring down the remote README so histories can be merged
git pull origin main --allow-unrelated-histories
# resolve any conflicts if prompted, then:
git push -u origin main
