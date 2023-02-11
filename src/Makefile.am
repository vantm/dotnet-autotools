.PHONY: my-api

my-api:
	dotnet publish \
		-o ../build \
		-r linux-x64 \
		-c release \
		-f net6.0 \
		--sc \
		-p:PublishSingleFile=true \
		-p:DebugType=embedded \
		my-api/my-api.csproj

all-local: my-api
