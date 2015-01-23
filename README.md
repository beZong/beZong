#beZong - organize your digital belongings

[TOC]

##Ideas

A bunch of ideas hanging for years. Those are dream features to organize Note, File, Folder, and Disk.

* **Hierarchical Notetaking** - WYSIWYG HTML editing, with file system hierarchy as storage.
* **File Explorer** -
	* file tagging
	* virtual search folder
	* synchronized browsing
* **Disk Analyzer** - live and snapshot statistics for file size, date, and etc ...
* **File Search** - by file name, location, size, date, and etc ..., and indexing for removable media (CD, DVD, USB drive)
* **Full Text Search** - 
* **Intelligent File/Folder Classification** - 
	* find files with similar name, size, and attributes
	* find folders with similar file sets


##Motivation
Many softwares have those features, while not well integrated together. 

For example:

* **Hierarchical Notetaking**

| \ | hierarchy | RTF/HTML editing | format | data migration |
|--------|--------|--------|--------|--------|
| Evernote | @@<br> limited layers | @@ <br>not good for table | @@<br> internal html| @ |
| Notational Velocity and alternatives | @@(@) | @(@)<br> not support external RTF pasting | @@(@)<br>text, html, markdown| @@(@) |
| Windows Live Writer, Zoundry Raven | @ tags | @@@ | @@<br>internal html | @@ |

* **Disk Analyzer**

| \ | size | date | folder browsing | snapshot |
|--------|--------|--------|--------|--------|
| Xinorbis | @@@ | @@@ | - | live & snapshot |
| JDiskReport | @@@ | @<br> relative date | @@@ | live & snapshot |
| WinDirStat | @@@ | - | @@ | live data only |
| sizeChecker | @@ | - | @ | live data only |
| diskusagereports | @@@ | @@@ | @@@ | snapshot only |


##Approach
Studying many softwares, to figure out how much I can benefit from those open source projects and some master-piece closed-source programs. Below is just a subset from my memo. 

The most important sources are:

* http://alternativeto.net/
* http://openhub.net/
* http://sourceforge.net/
* http://github.com/

| \ | node-webkit, js | C#, C++, .NET | Java | Python & others |
|--------|--------|--------|--------|--------|
| **Hierarchical Notetaking** | TiddlyWiki, TagSpaces, Laverna  | Evernote, Notational Velocity, nvALT, WLW, Tomboy | jNV | LoNote, nvpy, KeepNote, Zim-wiki, WikidPad, OutWiker, Zoundry Raven,  |
| **File Explorer** | nwkFilePlayer, CATS, Cloud Commander, <br> nw-sample-apps, firecommander | FileZilla, WinSCP, Explorer++,<br> Better Explorer, Midnight Commander | muCommander | CubicExplorer,<br> Double Commander |
| **Disk Analyzer** | sizeChecker | WinDirStat,<br> codeplex examples | JDiskReport | Xinorbis, diskusagereports |
| **File Search** | TagSpaces | Everything, Locate32, Listary |  | Launchy,<br>CD Index - 光碟索引大師 |
| **Full Text Search** |  | | DocFetcher | Searchmonkey |
| **Auto Classification** | | | | POPFile |


During 2014-10 to 2014-12, I checked many programming platforms, and then refined my preferences to:
* node-webkit, js 
* C#, C++, .NET 
* Java 
* Python


Thanks the valuable tutorial at [The Jackal of Javascript](http://thejackalofjavascript.com), I finaly find enough building block to start with node-webkit. The first step for me would be adding WYSIWYG HTML editing capability to one of below that already have file system hierarchy features

* **Node-Webkit File Player**
* **CATS** (coding IDE) 


## Reference
### node-webkit, JavaScript

* **TiddlyWiki** (js, node.js) - http://tiddlywiki.com/
* **TiddlyDesktop** - https://github.com/Jermolene/TiddlyDesktop
* **muComposer** (CKEditor WYSIWYG) - https://github.com/fabi1cazenave/muComposer
* **TagSpaces** (summernote WYSIWYG) - http://www.tagspaces.org/
* **Pensieve** (Aloha WYSIWYG) - https://github.com/lhl/pensieve
* **Laverna** (node.js, Markdown) - https://github.com/Laverna/laverna
* **sizeChecker** - https://github.com/airbob/sizeChecker 
* **CATS** (coding IDE) - http://jbaron.github.io/cats/
* nwkFilePlayer - **Node-Webkit File Player**, 
	* http://thejackalofjavascript.com/nwk-file-player/ (node-webkit)
	* http://thejackalofjavascript.com/file-browser-with-jstree-angularjs-and-expressjs/ (web)
* **Cloud Commander**
	* http://cloudcmd.io/
	* https://github.com/coderaiser/cloudcmd 
* file manager - 
https://github.com/zcbenz/nw-sample-apps/tree/master/file-explorer 
* **firecommander** (Firefox addon) -
	* https://code.google.com/p/firecommander/ 
	* https://addons.mozilla.org/en-US/firefox/addon/fire-commander 

###C#, C++, .NET
* **Notational Velocity** (OS X) - http://notational.net/
* **nvALT** (OS X) - http://brettterpstra.com/projects/nvalt/
* **Windows Live Writer** (WLW, .NET) - http://gog.is/Windows/Live/Writer/ (Google Search)
* **Tomboy** - https://wiki.gnome.org/Apps/Tomboy
* **FileZilla** (C++, wxWidgets) - http://en.wikipedia.org/wiki/FileZilla
* **WinSCP** - http://en.wikipedia.org/wiki/WinSCP
* **Explorer++** - http://en.wikipedia.org/wiki/Explorer%2B%2B
* **Better Explorer** (.NET) - http://better-explorer.com 
* **Midnight Commander** - http://en.wikipedia.org/wiki/Midnight_Commander
* **WinDirStat** - https://windirstat.info/
* **FolderSize** - http://foldersize.codeplex.com/ 
* **Disk Space Analyzer Demo Application** (C++, HTML5, QT) -http://www.codeproject.com/Articles/336018/Building-C-Applications-with-HTML 
* **Everything Search Engine** - http://www.voidtools.com/
* **Locate32** - http://locate32.cogit.net/
* **Listary** - http://www.listary.com/

###Java
* **jNV** - https://github.com/vinodkd/jNV
* **muCommander** - http://en.wikipedia.org/wiki/MuCommander
* **JDiskReport** - http://www.jgoodies.com/freeware/jdiskreport/
* **DocFetcher** - http://docfetcher.sourceforge.net/en/index.html

###Python
* **LoNote** - https://bitbucket.org/civalin/lonote
* **nvpy** - https://github.com/cpbotha/nvpy
* **KeepNote** - http://keepnote.org/
* **Zim-wiki** - http://zim-wiki.org/
* **WikidPad** - http://wikidpad.sourceforge.net/
* **OutWiker** - http://jenyay.net/Outwiker/English
* **Zoundry Raven** - http://www.zoundryraven.com/devblog/2009/02/zoundry-raven-open-source.html

###Others
* **CubicExplorer** (Pascal) - http://www.cubicreality.com/
* **Double Commander** (Pascal) - http://doublecmd.sourceforge.net/
* **Xinorbis** (Delphi) - http://www.xinorbis.com/
* **diskusagereports** (PHP) - http://diskusagereports.com/
* **CD Index - 光碟索引大師** -
* **Launchy** (QT) - http://www.launchy.net/
* **Searchmonkey** (gtk2) - http://searchmonkey.embeddediq.com/
* **POPFile** (perl) - http://getpopfile.org/










