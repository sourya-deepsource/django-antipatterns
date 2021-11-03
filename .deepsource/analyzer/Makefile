build:
	cp -r ../../. /app
	apk add python3-dev py3-pip build-base
	ln -s `which python3` /usr/bin/python3
	# install semgrep
	mkdir /toolbox/venv
	pip install --target=/toolbox/venv semgrep
