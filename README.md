# What is this?
This is a Powershell script PyExecGo uses to setup the Python "environment", it's used by [the builder](https://github.com/PyExecGo-Project/PyExecGo-Builder).

### This is the readme of the orignal creator (Dreamsavior), which can be found in the [LICENSE](https://github.com/PyExecGo-Project/pyportable/blob/main/LICENSE) file.
---

# What is this?
A powershell script to generate portable Python for windows system from a clean slate.

# What do you mean by "portable"?
The instance of non virtualized Python that is not dependent on the system path and can run independently. You can move python portable anywhere on your computer or to another computer. You can have more than one instance of portable python running simultaneously on your system. You can also have the combination of traditionally installed Python and portable Python.

The barebone of the Python portable is relatively small. It is not more than 9Mb in the 7z archive.

# How to use?
download portablepy.ps1 in a folder and run it. By default portablepy.ps1 will setup Python 3.9.10 in the same folder it is in.

### Without arguments
```.\portablepy.ps1```

### With optional arguments
```.\portablepy.ps1 -source "https://www.python.org/ftp/python/3.9.10/python-3.9.10-embed-amd64.zip" -destination "C:\SomeDir\PortablePython\"```


*) Path to a directory should always end with back space

You can find the list of Python's Binary packages for Windows here: https://www.python.org/downloads/windows/
Select the **Windows embeddable package** from the list.
