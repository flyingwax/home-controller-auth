# home-controller-auth

Static page served by GitHub Pages at https://flyingwax.github.io/home-controller-auth/.

Home Assistant's IndieAuth flow requires the OAuth `client_id` to be a public URL whose HTML
declares the allowed redirect URI. This page is that client identifier for the Home Controller
iOS app and declares `<link rel="redirect_uri" href="homecontroller://auth-callback">`.
