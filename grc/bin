#!/bin/bash

echo "=========================================================================="
echo "What is name you want to git to your new git repository ?"
read repo_name

echo "What is your github username ?"
read username

curl -u $username https://api.github.com/user/repos -d '{"name": "'${repo_name}'"}'

echo "git@github.com:$username/$repo_name.git is created"

echo "Thanks you for using grc. @drxos <sounton@gmail.com>"
echo "@drxos <sounton@gmail.com>"
echo "Bye!"
echo "=========================================================================="
