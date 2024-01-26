srpm:
	dnf -y install gcc gcc-c++ make rpm-build git cmake3
	mkdir build; cd build; cmake3 ..; cpack3 -G RPM --config ./CPackSourceConfig.cmake; cp *.src.rpm $(outdir)
