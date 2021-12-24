# R2NorthstarCN_Launcher
A repo for releaseing R2NorthstarCN Launcher for joining R2NorthstarCN Official servers. You can also do this by manually editing master server address in a Official R2NorthstarCN release.
# How to Install:
1.Download the latest Release from this repository.

2.Unzip everything to the root folder of your Titanfall2 install.

3.Run NorthstarLauncher.exe .
# How to manually edit from Official R2Northstar Releases.
1.Download and install the lastest version of R2Northstar Release.

2.Navigate to %Your_Game_Dir%\R2Northstar\mods\Northstar.CustomServers\mod\cfg, Open 'autoexec_ns_server.cfg' with any Text editor. An syntax-highlighted Text editor (Like vscode or notepad++) would be nice.

3.Find the original convar, and replace it with this:
```
ns_masterserver_hostname "tf2cn.wolf109909.top" // masterserver hostname
```
3.Do the same to another file located at %Your_Game_Dir%\R2Northstar\mods\Northstar.Client\mod\cfg\autoexec_ns_client.cfg
