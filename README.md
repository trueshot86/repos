# How to get list of repos.

curl -sS https://api.github.com/users/trueshot86/repos | grep "\"url\"" | grep repos
