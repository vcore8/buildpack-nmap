fix do problema dos scripts 


{"level":"error","error":"NSE: failed to initialize the script engine:\ncould not locate nse_main.lua\nstack traceback:\n\t[C]: in ?\n","warnings":["Unable to find nmap-services!  Resorting to /etc/services","NSE: failed to initialize the script engine:","could not locate nse_main.lua","stack traceback:","\t[C]: in ?","","QUITTING!"],"time":"2022-03-23T00:58:40Z","message":"unable to run nmap scan: NSE: failed to initialize the script engine:\ncould not locate nse_main.lua\nstack traceback:\n\t[C]: in ?\n"}




# buildpack-nmap
<a href="https://heroku.com/deploy?template=https://github.com/hahwul/buildpack-nmap">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a><br>
install nmap and set alias buildpack of heroku for me(add export ENV)

## Composed
```
$ heroku create --buildpack  https://github.com/hahwul/buildpack-nmap.git
$ git push heroku master
```
## setting config vars
`App => Settings => Config vars`
<img src="https://user-images.githubusercontent.com/13212227/65061836-b5910980-d9b5-11e9-94d4-4cb5b20929a7.png">

## References
https://github.com/socialpaymentsbv/heroku-buildpack-nmap
