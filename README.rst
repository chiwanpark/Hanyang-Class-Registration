Hanyang Class Registration
================================
Intro
-----
Unofficial Hanyang Registration for Python

Intallation
-----------

::

	pip install hanyang_registration
	
Quick Start
-----------
1. Login
~~~~~~~~~

::

    from hanyang_registration import sugang
    import logging
    
    # log_level default value is logging.INFO
    sinchung = sugang.Sinchung(log_lovel=logging.INFO)
    sinchung.login('2014036123', 'your_password')
    

2. Set Class Codes
~~~~~~~~~~~~~~~~~~~~~~

::
    
    sinchung.sugang_codes = ['12345', '12345', '12345', ...]
    
3. Register
~~~~~~~~~~~

::

    sinchung.register()

