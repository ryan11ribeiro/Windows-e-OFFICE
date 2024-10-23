# Windows-e-OFFICE
--------------------------------------------

TENTE ESSE PRIMEIRO PARA ATIVAR O WINDOWS E O PACOTE OFFICE :  
( irm https://get.activated.win | iex )
--------------------------------------------
PARA BAIXAR O OFFICE CASO OS APPS NÃO ESTEJAM INSTALADOS:
https://drive.google.com/file/d/1qIWkVxCjx3-i6acKY5wt0bqlysUz0RaU/view?usp=drive_link
--------------------------------------------

1- Open location of the Office installed on your PC.

cd /d %ProgramFiles%\Microsoft Office\Office16
cd /d %ProgramFiles(x86)%\Microsoft Office\Office16

2- for /f %x in ('dir /b ..\root\Licenses16\ProPlus2019VL*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"

3-
cscript ospp.vbs /setprt:1688
cscript ospp.vbs /unpkey:6MWKP >nul
cscript ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP
cscript ospp.vbs /sethst:e8.us.to
cscript ospp.vbs /act

-------------------------------------------
