panic: Get "https://api.intra.42.fr/v2/users/alex": oauth2: cannot fetch token: 401 Unauthorized
Response: {"error":"invalid_client","error_description":"Client authentication failed due to unknown client, no client authentication included, or unsupported authentication method."}

goroutine 19 [running]:
github.com/alexandregv/RP42/pkg/api.fetch({0xc0001a0040, 0xe})
	/home/alex/Téléchargements/RP42/pkg/api/api.go:19 +0x26a
github.com/alexandregv/RP42/pkg/api.GetUser({0xc0001a0008?, 0xc000180050?})
	/home/alex/Téléchargements/RP42/pkg/api/api.go:34 +0x6e
main.onReady()
	/home/alex/Téléchargements/RP42/cmd/RP42/main.go:130 +0x45
github.com/getlantern/systray.Run.func2()
	/home/alex/go/pkg/mod/github.com/getlantern/systray@v0.0.0-20190727060347-6f0e5a3c556c/systray.go:67 +0x32
created by github.com/getlantern/systray.Run
	/home/alex/go/pkg/mod/github.com/getlantern/systray@v0.0.0-20190727060347-6f0e5a3c556c/systray.go:65 +0xe5
