FDT-Free-IOS-AIR-Template
===========================================
A group of ant files that helps users of FDT5 Free Deploy IOS apps.

Basic Instalation process & info provided. Must Include a good tutorial ;-)


Features
----------------
- (New) Manage SDK's location between projects
- (New) Utility to merge AIR SDK with FLEX SDK
- (New) Manage entitlements
- (New) Option to debug with MonsterDebugger
- (New) Common InfoAddition List.
- (New) Added a "IOS.Publish last" ant target that lets you deploy with the last used Publish Settings
- (New) Moved all required fields to the first tab

- Provides deploying to all avaliable targets
- Deploy your ipa via USB to real device & iPhone Simulator
- Configure -platformsdk for Apple SDK's & iPhone Simulator deploying
- Autoincrement build number in Air Descriptor xml
- Enables an easy way to include custom Infoadditions
- Debug in Device & Simulator ( sort of, but it may help )
- Configure app icons
- Configure languages

Requeriments
----------------
OSX

Tested with latest version of FDT 5.6.2

Instalation
----------------

> Clone the git.

> Open a teminal window.

> Go to the cloned git dir.

> Type ant. Done!!!


Running
----------------         
> Create a new FDT Project.

> From the avaliable templates select: AIR FDT FREE > IOS FDT FREE

> Drop FDT.publish.settings.xml from build dir to the ant view.

> From ant view I recommend to "Hide internal targets". This way you only see the ant targets you need to use.

> First-run FDT.publish.settings.xml by double clicking it. ( Nothings happends is NORMAL )

> Go to Run > Externals tools > External tools Configurations

> Select JRE Tab and Select: Run in same JRE as the workspace.

> Double click FDT.publish.settings.xml

> IMPORTANT: Before you can do any action you must fill all the required fields

> With the Manage SDK's button you can configure the SDK's you have installed in your machine. This information now will be preserved between projects. Next time you create a new project SDK locations will be remembered.


Screenshots ( OLD not updated )
----------------  

![](https://raw.github.com/xperiments/FDT-Free-IOS-AIR-Template/master/images/01.png)

![](https://raw.github.com/xperiments/FDT-Free-IOS-AIR-Template/master/images/02.png)

![](https://raw.github.com/xperiments/FDT-Free-IOS-AIR-Template/master/images/03.png)

![](https://raw.github.com/xperiments/FDT-Free-IOS-AIR-Template/master/images/04.png)

![](https://raw.github.com/xperiments/FDT-Free-IOS-AIR-Template/master/images/05.png)
