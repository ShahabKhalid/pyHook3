# pyHook3  
  
Build  
---------  
- Download swig from http://www.swig.org/download.html  
- In Command prompt Run ` python setup.py build_ext --swig=[Path to swig executable]`
- Run `pip install .`

 Known bugs 
 ----------- 
- Nil  
    
Limitations 
------------ 
- pyHook3 will not work on Win9x (no messages show up) as it uses hooks which    
  are not present in Windows systems prior to NT 4.0 SP3.    
- pyHook3 will not work with **python2** , For python2 see pyHook's website, http://pyhook.sourceforge.net/.
