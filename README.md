# VHDX-Cleaner
Powershell Script to Cleanup automatically folder of VHDX users Profile for RDS Servers from Temp files, Downloads, RecycleBin...etc



# Inputs :
1- Directory for VHDX Files :
This script takes as input a directory for VHDX files , by default it's "C:\Temp\" and you can change directory if you want. here is the variable :
$VHD_Directory = "C:\Temp\"

2- Directory list to be cleaned :
in this script we can specify Directorys to be cleaned , in my case i used $Recycle.Bin and Download Directorys like this :
$recycle = '$RECYCLE.BIN' , 'Downloads' 
you can add more directorys if you want like this :
$recycle = '$RECYCLE.BIN' , 'Downloads' , 'AppData\Local\Temp'
