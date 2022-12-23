# agoraLMC
POC-Git Merge from different branches

Created 2 branches namely, **AgoraBranch** & **VeativeBranch** with basic setup including following files,
- index.html
- index.scss
- index.js

with differnt code in both branches.

After commiting different code snippets to individual branches. Created a new branch named, **VeativeAgora** to demonstrate git merge with following steps,

+ Checkout to VeativeAgoraBranch,
+ First merge using *git merge branch* as, > git merge AgoraBranch,
+ Second merge using above step as, > git merge VeativeBranch,
+ Since files are same in both branches, even line of code (LOC) is same, then there should be conflicts, which one should resolve based on code priority.
+ After resolving conflicts, simply add files using *git add filename(s)* as, > git add index.html index.js index.scss or simply > git add . (in case of all files),
+ Add commit message using *git commit -m "message"*, as > git commit -m "merge both veative and agora branches",
+ Branch updated with both AgoraBranch & VeativeBranch and ready to push/serve.

Thanks!
