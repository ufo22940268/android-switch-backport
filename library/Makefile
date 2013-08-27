.PHONY : main
main: 
	mvn -Dmaven.test.skip=true install -q

.PHONY : sample
sample: main
	$(MAKE) -C ../sample/


.DEFAULT_GOAL := sample
