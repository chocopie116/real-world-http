url=http://localhost:18888

server:
	go run server.go

test:
	curl --http1.0 $(url)/greeting

test2:
	curl --http1.0 --get --data-urlencode "search word" $(url)

test3:
	curl -v --http1.0 $(url)/greeting

test4:
	curl --http1.0 -H "X-Test: Hello" $(url)

test5:
	curl -v -d "{\"hello\": \"world\"}" -H "Content-Type: application.json" $(url)
