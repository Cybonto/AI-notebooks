# AI-notebooks
A collection of AI relevant notebooks

When you clone this repository, you need to initialize and update the submodules:
```
  git clone https://github.com/Cybonto/AI-notebooks.git
  cd AI-notebooks
  git submodule update --init --recursive
```
If the submodules get updates, you can pull changes in the submodules and then commit those changes in your main repository.
```
  cd submodules/some-repo
  git pull origin main
  cd ../..
  git add .
  git commit -m "Updated some-repo"
  git push origin main
```
To add a submodule, use the following command:
```
git submodule add https://github.com/other-user/other-repo.git path/to/other-repo
git submodule update --init --recursive
```
