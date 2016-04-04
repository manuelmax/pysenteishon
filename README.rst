pysenteishon
============

Control your presentations with the swipe of your finger!
Fork realizado de https://github.com/edvm/pysenteishon, el autor es Emiliano Dalla Verde Marcozzi @edvm,
la diferencia es que este funciona con Python 2.7, el original necesita Pytho 2

Install
=======

From GitHub
-----------

::
    
   git clone https://github.com/manuelmax/pysenteishon
   cd pysenteishon
   python pysenteishon/app.py

Windows
-------

You also need to install `pywin32
<https://sourceforge.net/projects/pywin32/>`_ to make it works
properly.

pysenteishon 1.0.0b was tested on Python 3.4.4 running Windows XP
32bits and pywin32 build 220.


Usage
=====

After running the app:

- Make sure you allow access to port 5000 in your firewall settings.

- Open your presentation PDF on your computer and leave it open (MAKE
  SURE the program that is running your presentation has FOCUS).

- Open a web browser with your cellphone and point it to your laptop
  ip address port 5000, for example: http://192.168.0.11:5000

- Swipe on your touchscreen and start your talk! :D

Options
=======

::

   usage: app.py [-h] [-p PORT] [-a user password]

   optional arguments:
     -h, --help            show this help message and exit
     -p PORT, --port PORT  Listen on port
     -a user password, --auth user password
                           Basic auth


