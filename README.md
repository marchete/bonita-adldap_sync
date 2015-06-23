# bonita-adldap_sync
Bonita BPM 6.5.X/7.0.X Active Directory / LDAP Synchronization<br/>

Bonita Active Directory Sinchronization process.<br/>
FEATURES:

-Synchronize from AD/LDAP to Bonita. Default config is for AD.<br/>
-Doesn't sync from Bonita to AD.<br/>
-Full or incremental sync.<br/>
-Sync Groups, Users or Both.<br/>
-Configurable Update Fields (from LDAP to Bonita)<br/>
-Configurable Group recreation: with/without full path, with regex....<br/>
-Single instance, doesn't fill up the archive process with tons of process.<br/>
-No foreign references, only standard ones. Doesn't require external storage.<br/>
-Tested both on Bonita BPM 6.5.1 and Bonita 7.0
<br/>
## Install
Import the .bos file in Bonita Editor, configure all the variables on the process and run it.<br/>
When it's working you can publish it and import to your Production environment.<br/>
All the variables have a description on Bonita, check it to know how to configure them.
## Screenshots
#### Process Diagram
<img src="/screenshots/diagram.png?raw=true" alt="Process diagram"/>
