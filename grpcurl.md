$ grpcurl.exe --proto ./hero/hero.proto -d '{ "id": 1 }' --plaintext localhost:5000  hero.HeroesService.FindOne
{
  "id": 1,
  "name": "John"
}

Lucho@LUCHO-PC MINGW64 /d/repos/bitbucket.org/luciano-andrade-md/grpc-demo (master)
$ grpcurl.exe --proto ./hero/hero.proto -d '{ "id": 2 }' --plaintext localhost:5000  hero.HeroesService.FindOne
{
  "id": 2,
  "name": "Doe"
}