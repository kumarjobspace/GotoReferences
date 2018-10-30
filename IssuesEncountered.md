
# MSDTC
## Got the below in error in event Viewer
* Message: The MSDTC transaction manager was unable to pull the transaction from the source transaction manager due to communication problems. Possible causes are: a firewall is present and it doesn't have an exception for the MSDTC process, the two machines cannot find each other by their NetBIOS names, or the support for network transactions is not enabled for one of the two transaction managers. (Exception from HRESULT: 0x8004D02B)
Data: System.Collections.ListDictionaryInternal
* Message: MSDTC on server 'HSA-DB-UAT1\TXN' is unavailable.

https://blog.sandro-pereira.com/2016/11/23/an-error-occurred-while-attempting-to-connect-to-a-remove-sql-server-database-the-local-ms-dtc-detected-that-the-ms-dtc-on-has-the-same-unique-identity-as-the-local-ms-dtc/

https://stackoverflow.com/questions/36547460/how-to-solve-msdtc-does-not-work-error-when-communicate-between-two-servers
