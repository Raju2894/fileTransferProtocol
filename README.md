----------------------------------------------    README      ---------------------------------------------------------
Application Level file sharing protocol with support for upload/download and indexed searching
------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------------
Compile using : cc -o ftp filename -lssl -lcrypto
---------------------------------------------------------------------
Run using
./ftp <client portno> <ip of server> <server portno> <protocol>

Commands Supported : 

IndexGet
ShortList

   
IndexGet
ShortList 
starting-time-stamp
ending-time-stamp   
IndexGet
RegEx
"*mp3"  


FileHash
Verify
Name-of-file

FileHash
CheckAll

FileDownload
Name-of-file

FileUpload
Name-of-file

-------------------------------------------------------------------------------------------------------


