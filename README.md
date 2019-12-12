nginx.conf
========
Recognizing [Kerchhoffs's principle], I hereby publish my own nginx
configuration files.

```bash
sudo ln -sf "$PWD/nginx.conf" /etc/nginx/
sudo ln -sf "$PWD/options-ssl-nginx.conf" /etc/letsencrypt/

# Test if everything is alright
sudo nginx -t -c /etc/nginx/nginx.conf
```

##### References
- http://nginx.org/en/docs/
- https://github.com/h5bp/server-configs-nginx
- https://github.com/yandex/gixy

[Caddy]: https://github.com/simnalamburt/Caddyfile
[Caddyfile]: https://github.com/simnalamburt/Caddyfile
[Kerchhoffs's principle]: https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle
