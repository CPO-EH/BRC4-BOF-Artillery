make:
	mkdir -p out64 out86
	x86_64-w64-mingw32-gcc contact_harvester.c -c -o out64/contact_harvester64.o
	i686-w64-mingw32-gcc contact_harvester.c -c -o out86/contact_harvester86.o

	x86_64-w64-mingw32-gcc cryptvortex.c -c -o out64/cryptvortex64.o
	i686-w64-mingw32-gcc cryptvortex.c -c -o out86/cryptvortex86.o

	x86_64-w64-mingw32-gcc mem_read.c -c -o out64/mem_read64.o
	i686-w64-mingw32-gcc mem_read.c -c -o out86/mem_read86.o

	x86_64-w64-mingw32-gcc mem_search.c -c -o out64/mem_search64.o
	i686-w64-mingw32-gcc mem_search.c -c -o out86/mem_search86.o

	x86_64-w64-mingw32-gcc shadowclone.c -c -o out64/shadowclone64.o
	i686-w64-mingw32-gcc shadowclone.c -c -o out86/shadowclone86.o

	x86_64-w64-mingw32-gcc proc_version.c -c -o out64/proc_version64.o
	i686-w64-mingw32-gcc proc_version.c -c -o out86/proc_version86.o

	x86_64-w64-mingw32-gcc dump_procargs.c -c -o out64/dump_procargs64.o
	i686-w64-mingw32-gcc dump_procargs.c -c -o out86/dump_procargs86.o

	x86_64-w64-mingw32-gcc get_netntlm.c -c -o out64/get_netntlm64.o
	i686-w64-mingw32-gcc get_netntlm.c -c -o out86/get_netntlm86.o

clean:
	rm -rf out64 out86