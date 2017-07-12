Steps Installation
------------------

1. Install java sdk.
2. Install nodejs.
3. Install python 2.
4. Install "android studio donwload"
5. Open command run as administrator.
6. Cek version node -v
7. Install react native command line tool 
	npm install -g react-native-cli
8. Change folder into your working space
9. Generate new app
	react-native init albums
   *album is nama app.
10. Open android studio.
11. Open existing project > albums.
12. Follow the process setup take time and more steps.
13. Setup Android emulator.
	Tools > Android > AVD Manager > Create Virtual Device
	Choose default nexus around 5 inch
	instal Haxm for better performance emulator.
	Run simulator
	Jump to solution
	Go to start menu > type & search system settings > view advanced system settings > Advanced tab > Environment Variables > New > type variable name: JAVA_HOME > value browser to jdk... file to C:\Program Files\Java\jdk1.8.0_131
14. Edit the PATH > C:\Users\dyo\AppData\Local\Android\sdk\platform-tools.
* you need to show hidden AppData! to get right path!
14. When finish click oke, oke 
15. Restart cmd
16. Point to folder dyo documents\workspace\reactnative\nameApp> react-native run-android

ERROR 1 - solved
-----

react-native is not recognized as an internal or external command, operable program or batch file.

path ori System Variable: C:\ProgramData\Oracle\Java\javapath;%SystemRoot%\system32;%SystemRoot%;%SystemRoot%\System32\Wbem;%SYSTEMROOT%\System32\WindowsPowerShell\v1.0\;C:\Program Files\7-Zip;C:\Program Files\PuTTY\;C:\Program Files\nodejs\

npm path : C:\Users\Dyo\AppData\Roaming\npm

bikin path nyambung 

ERROR 2 - solved
-------

'adb' is not recognized as an internal or external command, operable program or batch file

bikin path nyambung with ; tanpas spaci.

Error 3 - solved
-------
Could not get BatchdBridge, make sure your bundle is packaged correctly
 
solution: react-native start
          Open another cmd and run again react-natvie run-android
success!