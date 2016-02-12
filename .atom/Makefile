install-all-packages:
	cat packages.list | xargs apm install

packages.list: packages/*/
	ls packages/  | grep -v README.md > packages.list
