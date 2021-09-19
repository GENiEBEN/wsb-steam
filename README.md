# wsb-steam

Windows Sandbox configuration files to use with a secondary Steam account.

# How to use

Unpack the `WSB-Steam.zip` file then open `WSB-Steam.wsb` or `WSB-Steam+steamapps.wsb` in a text editor.
Replace the path in the first \<HostFolder\> tag to match the folder where the .zip has been unpacked.
  
Both configs will install a local theme, set Dark Mode and install Firefox and Steam. `WSB-Steam+steamapps.wsb` will also map the default installation
folder of Steam apps (C:\Program Files (x86)\Steam\steamapps) into the Sandbox, so you can access your installed games without having to redownload.

NOTE: If you do not use the default installation path for Steam under your host system, do not use the +steamapps config file, or edit it to match your steam library path.

# Customise
  
Apps installer is setup by ninite.com but you can add more under _Settings.bat or create a new installer on Ninite.
