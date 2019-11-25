# Week10-11
My attempt of week 10 and 11
First off, I downloaded and installed GoogleCloudSDKInstaller. I then initillized it and set the default zone and region to the one given in the instructions (us-central1 region and us-central1-f zone).  I then set up the firewall with the commands given to me and ran the command "gcloud compute ssh mhn-admin" which pulled up another window.  
Then I typed the command "sudo apt update" and got this error:
GPG error: http://downloads-distro.mongodb.org dist InRelease: Clearsigned file isn't valid, got 'NODATA' (does the network require authentication?)
![FirstError](week10-11/SudoAptUpdate.gif)
I then figured there was just something wrong with the update so I moved on and typed in the command "sudo apt install git python-magic -y" and was told that everything was up to date. 

Then I "cd /opt/", "sudo git clone https://github.com/pwnlandia/mhn.git", and "cd mhn/"
Finally I ran "sudo ./install.sh" and got the same error as before:
GPG error: http://downloads-distro.mongodb.org dist InRelease: Clearsigned file isn't valid, got 'NODATA' (does the network require authentication?)

So, something was wrong.  I googled the error to see what I could do to solve the issue:
I found these websites and none of them either pertained to me or didn't work. (I did the ones I thought didn't pertain to me just to be safe.
https://community.ui.com/questions/MongoDB-NODATA-Clearsigned-file-isnt-valid-on-update-Debian/9a702607-95c4-4d62-8379-0e224389a780
https://askubuntu.com/questions/486113/gpg-error-clearsigned-file-isnt-valid-when-installing-mongodb?noredirect=1&lq=1
https://askubuntu.com/questions/486113/gpg-error-clearsigned-file-isnt-valid-when-installing-mongodb
https://www.bigbrus.com/2017/04/09/gpg-error-clearsigned-file-isnt-valid-got-nodata/
https://stackoverflow.com/questions/24487165/inrelease-clearsigned-file-isnt-valid-got-nodata-does-the-network-require

So, I assumed something was wrong with my laptop. So, I deleted everything and went to my desktop to try there.  But the same error kept popping up. 
GPG error: http://downloads-distro.mongodb.org dist InRelease: Clearsigned file isn't valid, got 'NODATA' (does the network require authentication?)

I would also like to note that I did this assignment on mulitple different networks and wifi's (mainly the schools) and none of them worked. 
So, that is as far as I got. I appologize for not having anything more.
