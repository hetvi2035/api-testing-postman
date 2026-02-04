# api-testing-postman

## Project Title: GitHub & Postman Assessment

## Tool Used: Git, GitHub, Postman

## APIs Tested:

GET request 1: https://jsonplaceholder.typicode.com
GET request 2: https://reqres.in
POST request: https://jsonplaceholder.typicode.com/posts/1
PUT request: https://jsonplaceholder.typicode.com/posts/1
Environment variable baseUrl: https://jsonplaceholder.typicode.com/posts/1
Basic test: https://jsonplaceholder.typicode.com/posts/1


## Git command used:

mkdir api-testing-postman
cd api-testing-postman

git init

echo "# api-testing-postman" >> README.mkdir
echo "# api-testing-postman" >> file1.txt

git branch -M main
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/hetvi2035/api-testing-postman.git
git remote -v
git push -u origin main

git branch
git branch feature-branch
git checkout feature-branch
git log

echo "commit" >> file1.txt
git add file1.txt
git commit -m "commit"
