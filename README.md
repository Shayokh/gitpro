This is a sample project to test some scripting skills regarding Git.

Commands:

->mkdir testpro
->cd testpro
->git init
->echo testpro > README.md
->git add README.md
->git commit -m "initial commit"
->git remote add origin https://github.com/Shayokh/gitpro
->git branch -M master
->git push -u origin master
->git checkout -b feature-1
->touch test.md
->git add test.md
->git commit -m "add test file"
->git checkout master
->git checkout -b feature-2
->echo "Sample Test File" > test2.md
->git add test2.md
->git commit -m "add test2 file"
->git branch -d feature-1
->git checkout master
->git branch -d feature-2
->git push origin --delete feature-1
->git push origin --delete feature-2

END