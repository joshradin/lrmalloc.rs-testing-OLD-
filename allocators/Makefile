TARGET =  build-Hoard build-ptmalloc build-jemalloc build-SuperMalloc build-ralloc
CLEANERS =  clean-Hoard clean-ptmalloc clean-jemalloc clean-SuperMalloc clean-ralloc


#all:
#	make $(TARGET)

# build-tcmalloc:
# 	cd gperftools && ./configure && make

build-Hoard:
	cd Hoard/src && make && cd ..

build-jemalloc:
	cd jemalloc && ./autogen.sh && make && cd ..

build-ptmalloc:
	cd ptmalloc3 && make && cd ..

build-SuperMalloc:
	cd SuperMalloc && make && cd ..

build-ralloc:
	cd ralloc && make && cd ..

clean:
	make $(CLEANERS)

# clean-tcmalloc:
# 	cd gperftools && make clean && make distclean

clean-Hoard:
	cd Hoard/src && make clean && cd ..

clean-jemalloc:
	cd jemalloc && make clean && cd ..

clean-ptmalloc:
	cd ptmalloc3 && make clean && cd ..

clean-SuperMalloc:
	cd SuperMalloc && make clean && cd ..

clean-ralloc:
	cd ralloc && make clean && cd ..
