## Build  
* download  
git clone https://github.com/tongbai168/v8.git  
https://github.com/weimingtom/v8  

* Source encoding  
Change src/objects.cc from utf8 to ansi using Notepad++  

* Generate sln files:  
python build/gyp_v8.py (gyp not need install???)   

## Install gyp before building    
* if under build/ folder, not need, see  
https://github.com/tongbai168/v8/tree/master/build/gyp  
* if not exists, see  
https://github.com/svn2github/gyp  
execute 'python setup.py install'  

## Status  
Run shell.exe success  
