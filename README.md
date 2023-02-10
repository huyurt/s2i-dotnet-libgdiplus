# s2i-dotnet-libgdiplus

````powershell
choco install make

cd .\6.0\build
make build

docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]
docker push NAME[:TAG]
````

