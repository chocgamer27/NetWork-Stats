# NetWork Stats
Its a simple website that pings cloudflare (https://cloudflare.com/cdn-cgi/trace) to get the ping, it also uses ipify to get the ip then ipwho.is to find the country and city of the ip.
it shows a colour depending on ping
Green: 0-80
slightly yellow greeen: 81-150
yellow: 151-250
orange: 251-400
red: 400+

I made it with html and javascript (as its the language in <script>), I made it to test my ping, I faced the problem described below (google extension blocking it) it was a simple fix by disabling the extension temporarily. Fairly simple project thats why it only took about an hour.

-- with testing I figured out it doesnt work with the settings I had on ublock origin (google chrome extension, adblocker, stops auto redirects, etc)
-- so if its not working try disabling extensions and adblockers like that
-- why does it work like that? I dunno
-- the warning in console would be ERR_BLOCKED_BY_CLIENT
