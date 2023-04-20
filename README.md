# fix-math-inline-hugo-theme-next
- Supports inline mathematical formulas.

- The original theme did not support inline mathematical mode, so I went to the Mathjax.js official website to review the document and modify the Mathjax.js file. 

- At the same time, remove complex website statistics and simplify them before moving them to the bottom of the webpage. 

- The hugo version is `hugo_extended_011.3_windows-amd64. zip`

## useage

- install hugo

- preview

  `hugo server`

- change the config file

  `baseURL = "https://<your-github-name>.github.io/"`
  
- build
  `hugo`
  
- git pull to github
  ```nginx
  cd public
  git init    ## init repo
  git remote add origin https://github.com/<your-github-name>/<your-github-name>.github.io.git    ## connect remote repo
  git add .
  git commit -m "first commit"
  git push -u origin master
  
  ```

- update your article

  ```nginx
  cd public
  git add .
  git status
  git commit -m "<Information for each blog>"
  git push
  ```

  - new blog
  ```
  hugo new post/<filename>/index.md   # easy to insert image wiht Typora
  # or
  hugo new post/<filename>.md
  ```
  

