# redirect-url

Simple Docker container to redirect a url when the server is hit.  Setup so you can do something like redirect `discord.yoursite.com` to your discord invite link.

Done using [nginx](https://www.nginx.com/) to keep things simple.

Setup:
1. Set `REDIRECT_ADDRESS` environmental variable to the URL to redirect to
2. Deploy somewhere
3. Point your URL in DNS to the service