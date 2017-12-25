url=http://localhost:18888

test:
		curl -v --http1.0 -d title="Head First PHP & MySQL&author=Lynn Beighley, Michael Morrison" $(url)

test2:
		curl -v --http1.0 --data-urlencode title="Head First PHP & MySQL" --data-urlencode author="Lynn Beighley, Michael Morrison" $(url)

test3:
		curl -v --http1.0 -F title="The Art of Community" -F author="Jono Bacon" -F attachment-file=@test.text $(url)

test4:
		curl -v --http1.0 -F title="The Art of Community" -F author="Jono Bacon" -F "attachment-file@test.text;type=text/html" $(url)

test5:
		curl -v --http1.0 -F title="The Art of Community" -F author="Jono Bacon" -F "attachment-file@test.text;filename=sample.txt" $(url)

test6:
		curl -v --http1.0 --compressed  $(url)

test7:
		curl -v --http1.0 -c cookie.txt -b cookie.txt -b "name=value" $(url)/cookie

test8:
	curl -v --http1.0 --basic -u user:pass  $(url)

test9:
	curl -v http1.0 --digest -u user:pass $(url)/digest
