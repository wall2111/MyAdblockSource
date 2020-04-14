# MyAdblockSource

Config adblock v4
```
"thanhnt_adblock": {
		"url": "https://raw.githubusercontent.com/wall2111/MyAdblockSource/master/black_hosts.txt",
		"rule": "/^127\\.0\\.0\\.1[[:space:]]+([[:alnum:]_-]+\\.)+[[:alpha:]]+([[:space:]]|$)/{print tolower($2)}",
		"size": "S",
		"focus": "My custom blacklist domains",
		"descurl": "http://blog.thanhnt.com"
}
```
