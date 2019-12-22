# sensord
Feed pressure sensor information to xcsoar. This is a clone of http://git-ro.openvario.org/sensord.git. sensord daemon converts
the information of pressureo sensors of Openvarion hardware to NMEA format and sends to tcp port 4353.
You may confifgure one of xcsoar devides to sensord. For example, config -> devices -> C: -> edit -> port: TCP port, tcp port: 4353.
driver: OpenVario -> ok -> close.

Armbian branch is for Armbian
