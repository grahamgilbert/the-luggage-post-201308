USE_PKGBUILD=1
include /usr/local/share/luggage/luggage.make

TITLE=Desktop_Icons
PACKAGE_NAME=Desktop_Icons
REVERSE_DOMAIN=com.grahamgilbert
PAYLOAD=\
	pack-server\
	pack-Library-Management-scriptRunner-once-Desktop_Icons_201308
	
pack-server:
	@sudo mkdir -p ${WORK_D}/Library/Management/Desktop_Icons
	@sudo ${CP} File\ Server.afploc ${WORK_D}/Library/Management/Desktop_Icons/File\ Server.afploc
	@sudo chown root:wheel ${WORK_D}/Library/Management/Desktop_Icons/File\ Server.afploc
	@sudo chmod 644 ${WORK_D}/Library/Management/Desktop_Icons/File\ Server.afploc