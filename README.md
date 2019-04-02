# getNewCleanVersion

Copy and paste one of the 2 line to your bash terminaland press Enter

1)[Add bash Command to your current user account]
```
cd;git clone https://github.com/YXY-git-hub/getNewCleanVersion2.git;bash getNewCleanVersion2/settingUpEnv;cd;installF;exec bash;
```
<pre>
  [Removing newVersion]
  ```
  cd;mv ~/getNewCleanVersion2/uninstallF .;rm -rf getNewCleanVersion2;bash uninstallF;rm -f uninstallF
  ```
</pre>
2)[Add bash Command to the root account]
```
git clone https://github.com/YXY-git-hub/getNewCleanVersion2.git;sudo cp getNewCleanVersion2/{newVersion,uninstallF} /bin;sudo chmod 755 /bin/newVersion;bash getNewCleanVersion2/installF;rm -rf getNewCleanVersion2;
```
<pre>
  [Removing newVersion]
  ```
  sudo rm /bin/newVersion;uninstallF;sudo rm -f uninstallF
  ```
</pre>
Now,you should be able update your package list,upgrade,dist-upgrade and clean up your system automatically with the command 'newVersion'
</pre>
