#  This is an Automated Animation Compression Script Documentation

* Set Arguments 
```

```
* Set pre-commit.bat
```
rem REPOS-PATH (the path to this repository)
set REPOS=%1
rem REV (the number of the revision just committed)
set REV=%2

set HOOK_DIR="C:/Repositories/ACLCustom/hooks"
set PYTHON_BIN="D:\python3_6_8\python.exe"
%PYTHON_BIN% %HOOK_DIR%/AnimCompress.py %REPOS% %REV%

```
