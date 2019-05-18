# LFI2RCE
race condition exploit for default php installs where LFI is present

This is a joint work by j1mx(https://github.com/J1mX) and myself
The script is skid safe. 

idea itself came from 
https://gynvael.coldwind.pl/download.php?f=PHP_LFI_rfc1867_temporary_files.pdf
and
https://insomniasec.com/downloads/publications/LFI%20With%20PHPInfo%20Assistance.pdf

If you know what to do with the script and have got lfi you should be able to get RCE with this exploit providing file_uploads=on in php.ini.... 


