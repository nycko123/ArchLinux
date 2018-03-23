# ArchLinux physlock - lightweight linux console locking tool (tty and Xserver)
version 11

	-d	fork and detach, parent returns after everything is set up
		(useful for suspend/hibernate scripts)
	-l	only lock console switching
	-L	only enable console switching
	-m	mute kernel messages on console while physlock is running
	-p MSG	Display MSG before the password prompt
	-s	disable sysrq key while physlock is running
