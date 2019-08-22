# Queries

a) [Issue](https://codesandbox.io/s/cool-hermann-hncn2)

Unable to use State properly in the comp when I use HOC on it.


b) Want to useState properly
[Issue](https://codesandbox.io/s/pensive-lumiere-lggyy)

Actually seState() promotes asynchronous updates to state as we know.
It achieved synchronous update when used promise. And also achieved synchronous update for counter in class comp using async/await.
But could not achieve the same scenario for useState. For useState, I need to compulsory follow reading the updated value in corresponding useEffect as like reading data in setState callback.Is there anything I am missing or correct me if I used bad approach or syntax. 


c) [Code](https://codesandbox.io/s/dazzling-bas-rwm88)
    Can HOC and RenderProps be together used on a component. ## MISCONCEPTION I guess.
    In the above example I want to create a HOC for DataFetcher to separate the Loading and data display logic. Is this a valid scenarion? Can u give me the rough overall idea to develop.    
    When we already have Render Props we can implement the logic of returning Loading or Error component
    [github code is in this link](https://github.com/Tirunagari-Harika/react-api-data-display/tree/master/RenderProps)
    
    
    
   NPM CONFIG FILE
   
   type : npm config edit
   This will open .npmrc file and these will be the params in it.
   
   
   ;;;;
; npm userconfig file
; this is a simple ini-formatted file
; lines that start with semi-colons are comments.
; read `npm help config` for help on the various options
;;;;

http-proxy=http://name:password@bcproxy.sgp.dbs.com:8080
https-proxy=http://name:password@bcproxy.sgp.dbs.com:8080/
strict-ssl=false

;;;;
; all options with default values
;;;;
; access=null

; allow-same-version=false

; always-auth=false

; also=null

; audit=true

; audit-level=low

; auth-type=legacy

; bin-links=true

; browser=null

; ca=null

; cafile=undefined

; cache=C:\Users\vijaychandar\AppData\Roaming\npm-cache

; cache-lock-stale=60000

; cache-lock-retries=10

; cache-lock-wait=10000

; cache-max=null

; cache-min=10

; cert=null

; cidr=null

; color=true

; depth=null

; description=true

; dev=false

; dry-run=false

; editor=notepad.exe

; engine-strict=false

; force=false

; fetch-retries=2

; fetch-retry-factor=10

; fetch-retry-mintimeout=10000

; fetch-retry-maxtimeout=60000

; git=git

; git-tag-version=true

; commit-hooks=true

; global=false

; globalconfig=C:\Users\vijaychandar\AppData\Roaming\npm\etc\npmrc

; global-style=false

; group=0

; ham-it-up=false

; heading=npm

; if-present=false

; ignore-prepublish=false

; ignore-scripts=false

; init-module=C:\Users\vijaychandar\.npm-init.js

; init-author-name=

; init-author-email=

; init-author-url=

; init-version=1.0.0

; init-license=ISC

; json=false

; key=null

; legacy-bundling=false

; link=false

; local-address=undefined

; loglevel=notice

; logs-max=10

; long=false

; maxsockets=50

; message=%s

; metrics-registry=null

; node-options=null

; node-version=10.15.2

; offline=false

; onload-script=null

; only=null

; optional=true

; otp=null

; package-lock=true

; package-lock-only=false

; parseable=false

; prefer-offline=false

; prefer-online=false

; prefix=C:\Program Files\nodejs

; preid=

; production=false

; progress=true

; proxy=null

; https-proxy=null

; noproxy=null

; user-agent=npm/{npm-version} node/{node-version} {platform} {arch}

; read-only=false

; rebuild-bundle=true

; registry=https://registry.npmjs.org/

; rollback=true

; save=true

; save-bundle=false

; save-dev=false

; save-exact=false

; save-optional=false

; save-prefix=^

; save-prod=false

; scope=

; script-shell=null

; scripts-prepend-node-path=warn-only

; searchopts=

; searchexclude=null

; searchlimit=20

; searchstaleness=900

; send-metrics=false

; shell=C:\WINDOWS\system32\cmd.exe

; shrinkwrap=true

; sign-git-commit=false

; sign-git-tag=false

; sso-poll-frequency=500

; sso-type=oauth

; strict-ssl=true

; tag=latest

; tag-version-prefix=v

; timing=false

; tmp=C:\Users\VIJAYC~1\AppData\Local\Temp

; unicode=false

; unsafe-perm=true

; update-notifier=true

; usage=false

; user=0

; userconfig=C:\Users\vijaychandar\.npmrc

; umask=0

; version=false

; versions=false

; viewer=browser

; _exit=true

; globalignorefile=C:\Users\vijaychandar\AppData\Roaming\npm\etc\npmignore








