# CdeBinPkg
separate CdeLib.lib and CdeServicedrivers from CdePkg to be edk2-staging compatible


## Revision history
### 20191126
* add Torito C Library R149: https://github.com/KilianKegel/torito-C-Library#20191126r149
* fixed functions snprintf() and vsnprintf() return value: ```number of characters that would have been written had n been sufficiently large```