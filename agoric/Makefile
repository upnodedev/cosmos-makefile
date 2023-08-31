setup:
	yarn install && yarn build

install-cosmic-swingset:
	cd packages/cosmic-swingset && $(MAKE)

build-cosmic-swingset:
	cd packages/cosmic-swingset && $(MAKE) build-chain

build: setup build-cosmic-swingset

install: setup install-cosmic-swingset
