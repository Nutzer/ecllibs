
all: anm ecl std

ecl:$(wildcard *.ecl)
anm:$(wildcard *.anm)
std:$(wildcard *.std)

%.ecl:%.ect
	thecl -I "/home/nutzer/Source/uniecl/KaECL/impl/data/include" -c 125 $< $@

%.anm:%.ant
	thanm -c $@ $<

%.std:%.stt
	thstd -c $< $@
