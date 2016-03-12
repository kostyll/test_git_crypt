 505  cd ~/workspace/
  506  mkdir test_gc_2
  507  cd test_g
  508  cd test_gc_2/
  509  ls
  510  git init
  511  git-crypt keygen key.bin
  512  zip -1 -e key.zip key.bin 
  513  cp ~/workspace/test_git_crypt/.gitattributes .
  514  vim.tiny dummy.json
  515  vim.tiny dummy.md
  516  git add dummy.json 
  517  git add dummy.md 
  518  git add key.zip 
  519  git add .gitattributes 
  520  git commit -am "initial commit"
  521  git status 
git remote add origin git@github.com:kostyll/test_git_crypt.git
git push -u origin master
