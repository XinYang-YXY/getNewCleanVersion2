# getNewCleanVersion

Copy and paste one of the 2 line to your bash terminaland press Enter

1)[Add bash Command to your current user account]
```
cd;git clone https://github.com/YXY-git-hub/getNewCleanVersion2.git;bash getNewCleanVersion2/settingUpEnv;cd;exec bash;installF
```
<pre>
  [Removing newVersion]
  ```
  cd;restorePath;rm -rf getNewCleanVersion2;
  ```
</pre>
2)[Add bash Command to the root account]
```
git clone https://github.com/YXY-git-hub/getNewCleanVersion2.git;sudo cp getNewCleanVersion2/newVersion /bin;bash installF;rm -rf getNewCleanVersion2;sudo chmod 755 /bin/newVersion
```
<pre>
  [Removing newVersion]
  ```
  sudo rm /bin/newVersion
  ```
</pre>
Now,you should be able update your package list,upgrade,dist-upgrade and clean up your system automatically with the command 'newVersion'
</pre>
