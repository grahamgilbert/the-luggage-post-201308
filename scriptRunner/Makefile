USE_PKGBUILD=1
include /usr/local/share/luggage/luggage.make
TITLE=scriptRunnerPkg
REVERSE_DOMAIN=com.grahamgilbert
PAYLOAD=\
	pack-scriptRunner\
	pack-Library-LaunchAgents-com.grahamgilbert.scriptrunner.plist

REPO_URL=https://github.com/natewalck/Scripts.git

pack-scriptRunner: l_usr_local_bin
	@sudo git clone ${REPO_URL} natewalck-scripts
	@sudo ${CP} natewalck-scripts/scriptRunner.py ${WORK_D}/usr/local/bin/scriptRunner.py
	@sudo chmod 755 ${WORK_D}/usr/local/bin/scriptRunner.py
	@sudo chown root:wheel ${WORK_D}/usr/local/bin/scriptRunner.py
	@sudo rm -rf natewalck-scripts