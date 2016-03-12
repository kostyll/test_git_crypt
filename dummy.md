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

 git-crypt init key.bin 
  532  git status 
  533  git diff
  534  git rm dummy.json 
  535  git rm dummy.json --cached 
  536  git-crypt init key
  537  git status 
  538  rm dummy.json 
  539  git status 
  540  git commit -am "..."
  541  git status 
  542  git-crypt init key.bin 
  543  git status 
  544  touch dummy.json
  545  git status 
  546  vim.tiny dummy.
  547  ls
  548  vim.tiny dummy.json 
  549  git status 
  550  git add dummy.json 
  551  git status 
  552  history 

