# Avro phonetic in ibus
Avro phonetic implementation in ibus.
Now in early stage of development, but its pretty usable.

==================================================================================

Developed By: 
IBus Engine: Sarim Khan <sarim2005@gmail.com>
Avro Phonetic Library: Rifat Nabi @torifat

==================================================================================

Licensed under MPL

==================================================================================

How to install :

 1. Open terminal/package manager and install following packages:

	git
	libibus-1.0-dev
	
    You'll need all related build tools like automake,autoconf etc...
    and Latest ibus from git compiled with gobject-introspection support enabled.

 2. Now give the following commands step-by-step:

	git clone git://github.com/sarim/ibus-avro.git
	cd ibus-avro
	aclocal && autoconf && automake
	./configure --prefix=/usr
	sudo make install

===================================================================================

How to enable and use :

 1. Open ibus Preferences (Applications->system tools->ibus under gnome-shell)
 2. Go to Input method -> select an input method -> Bengali -> Avro
 3. Now Click Add button to add Avro in the list
 4. Now restart ibus from Top Panel icon (Right click -> restart)
 5. Now Press Ctrl+Space to toggle between English and Avro (Bengali)
 6. Enjoy Avro Phonetic!

=====================================================================================
