#Dependencies:

	- To refresh all the dependencies run:
		- dotnet restore

#Add user secrets:

	- dotnet user-secret init
	- dotnet user-secret set "Connection:Password" "yourpassword"
	- dotnet user-secret set "Crypto:Secret" "your secret goes here"
