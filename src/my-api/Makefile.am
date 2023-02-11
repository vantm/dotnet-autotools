.PHONY: my-api

my-api:
	dotnet publish \
		-o bin/net6.0/publish \
		-r linux-x64 \
		-c release \
		-f net6.0 \
		--sc \
		-p:PublishSingleFile=true \
		-p:DebugType=embedded 
	cp bin/net6.0/publish/my-api my-api

all-local: my-api
