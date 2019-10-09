# Example ansible script to deploy an example flask application

## Requirements

This example uses features in ansible 2.6.1. Install this version to run the example.

## Deploy to server

Deploy using default branch:
```
ansible-playbook --inventory hosts playbook.yml
```

Deploy using another branch
```
ansible-playbook --extra-vars "git_branch=${GIT_BRANCH}" --inventory hosts playbook.yml
```

## View interface
Link http://51.158.106.134:5000/