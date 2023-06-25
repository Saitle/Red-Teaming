<h1>Powershell Empire: Important C2 Commands to Look For</h1>

**Empire PowerUp Module:**

 `usermodule privesc/powerup/allchecks`

**we need to build an OSX Macro payload**

 `usestager osx/macro`
 
 `usemodule collection/osx/browser_dump`
 
 `usemodule collection/osx/keylogger`

 `usemodule collection/osx/webcam`

**Active Direktory**

 `situational_awareness/network/powerview/get_user`

 `situational_awareness/network/powerview/get_group_member`

 `situational_awareness/network/powerview/get_computer`

 `usemodule situational_awareness/network/bloodhound`

 `situational_awareness/network/powerview/find_localadmin_access`

**Pass-The-Hash**

 `Empire Module: powershell/credentials/powerdump`

**DCSync Attack**  

 `Module for Empire: powershell/credentials/mimikatz/dcsync_hashdump`

 

 
