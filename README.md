# Setup gh-pages branch
    cd /path/to/repo-name
    git symbolic-ref HEAD refs/heads/gh-pages
    rm .git/index
    git clean -fdx
    echo "My GitHub Page" > index.html
    git add .
    git commit -a -m "First pages commit"
    git push origin gh-pages
