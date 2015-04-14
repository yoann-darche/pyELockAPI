pyELockAPI Lib - A simple API to interface Python with the ELock card from Elektor (April 2014)
===============================================================================================

This module include ELock object that permit to initiate a secure communication between the python script and the
ELock card. So basic function has been added to get the temperature value, or set the relay state.

How to install:
---------------

   python setup.py install

How to use :
------------

    Before using you need to have the appropriate certificate and key. In the following code we make assumption that you
    have the following files :

      * ISLclient-cert.pem : TLS Client certificate
      * ISLclient-key.pem  : Client KEY
      * cacert.pem         : CA Certificate

      Please see the following documentation (Config Elock - Detailed steps.pdf) for more information on How to
      generate and setup these certificates.
