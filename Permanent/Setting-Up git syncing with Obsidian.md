---
title: Setting-Up git syncing with Obsidian
date: 2026-07-10
tags:
  - "#guide"
  - "#linux"
  - "#obsidian"
  - "#windows"
slip box: "[[Guide]]"
---
## --------------------------------Note--------------------------------

For Windows/Linux

1. Install Git plugin 
2. Create a Bare repo 
3. Clone the repo in the Desired folder 
4. run the following in there

   ``` 
   git add .
   ```

   ```
   git commit -m "initial"
   ```

   ```
   git config set credential.helper manager
   ```


5. Go to Obsidian create a file for differentiation from the repo and push. 
   > It will ask for credentials you should type in username 
   >    - Username : Usual 
   >    - Password : Use [personal access token](https://github.com/settings/apps) (not normal acc password). 

6. Done

--- 

For Android/Phone 

1. Install [Gitsync](https://play.google.com/store/apps/details?id=com.viscouspot.gitsync&hl=en-US) plugin 
2. Setup is easy enough 
3. Remember to Choose "Nested folder"  
4. Done... 



## ------------------------Connected Ideas-------------------------  





## ----------------------Reference and Source-----------------------


- [Obsidian-Git-Docs](https://publish.obsidian.md/git-doc/Start+here#Git+plugin+Documentation)   

