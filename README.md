# software_development
## Phases to commit:
1- Create a local branch "git checkout -b <NAME>", the "NAME" should be in the following format: "sw_<feature_name>_v<version>"

2- Commit the changes with some description "git commit -m "my description""

3- Now send the branch using "git push origin sw_<feature_name>_v<version>"

## Merge to master:
Now, the branch is visible, and another SW developer should review / approve the changes:

1- You can suggest changes, and the developer must create a new branch with a new <version>.

2- If everything is OK you can merge the branch to the master using: "git pull source sw_ <function_name> _v <version>" in the master branch

## Notes:
Git refusing to merge unrelated histories, so in this case use "--allow-unrelated-histories"
