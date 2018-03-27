# USB-Boot-Authentication
Provided authentication to Unix-based systems such as NetBSD and MINIX 3 by incorporating a uniquely keyed USB device as part
of the boot process, thus adding an additional layer of security to such systems.


For my project, I edited the Linux kernel boot process to ensure that a user insert a uniquely-keyed USB device, as
part of the authentication process. If the user fails to provide the required device, the boot process would stop, preventing the machine from booting normally until the device was inserted. I wanted to develop a system that added an additional layer of security on top of the password authentication system that is already present in GNU Linux. The new layer of security would be keyed based on something that the user possessed (the USB drive) rather than just something the user knew (a password).
