wsdlDocument
============

This is a modification to wsdlDocument.php (http://code.google.com/p/wsdldocument/) written by Renan de Lima. 
It generates a WSDL file used for SOAP web services.

I works very well for complex types, but there is an issue where the WSDL file doesn't describe any arrays of tns types.
I added a few lines and it seems to have corrected the issue. I posted it here since I couldn't post it back to the 
original project page.