importStar
==========
Imagine...

* you need all modules in a package imported
* ... maybe because you want to access them via inspect.getmembers 
* ... or want to do sth. like for module in package: ...
* BUT:

	* you are to lazy to update all your __init__.py
	* you dont want/can't to use automodinit (https://github.com/ned14/automodinit)
	* AND/OR you cannot use dynamic imports (maybe because you want to create an application with pyinstaller)

THAN: this might be your solution!

install
=======
via pip
-------
TODO

ubuntu or simular
-----------------
sudo python setup.py install

windows
-------
python setup.py install


usage
=====
either:
* use as a script:
importstar [directorypath]
run importstar without further arguments or with -h to see help

* OR call function importStar.importstar.run(args)

