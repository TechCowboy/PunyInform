all: runtests

runtests:
	ruby runtests.rb

inform:
	inform -v8 -D test-gprheld.inf
	frotz test-gprheld.z8

test-issue107:
	inform +../lib -v3 test-issue107.inf
	frotz test-issue107.z3

test-unknownverb:
	inform +../lib -v3 test-unknownverb.inf
	frotz test-unknownverb.z3

indistiguishable:
	inform +../lib -v3 indistiguishable.inf
	frotz indistiguishable.z3

large3:
	inform +../lib -v3 largegame.inf
	frotz largegame.z3

large5:
	inform +../lib -v5 largegame.inf
	frotz largegame.z5

test-chooseobjectsfinal:
	inform +../lib -v5 -s -S -D test-chooseobjectsfinal.inf
	frotz test-chooseobjectsfinal.z5

test-panels:
	inform +../lib -v3 -s test-panels.inf
	frotz test-panels.z3

clean:
	rm -f *z3 *z5 *z8 *scr *output *messages
