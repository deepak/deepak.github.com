## Captain's Logbook

### Monday, Jan 12, 2015

- create project using classic html5-boilerplate.
  using html5 shiv and not modernizer
- knew about running a local webserver using python
  ie. python -m SimpleHTTPServer 8080
  it asks for port permission, "allow to access incoming network requests"
  can do the same with ruby by
  ruby -run -e httpd . -p 8080
  did not ask for port permission now. because i use ruby for
  day-to-day work and had given this permission before
- create favicon. took normal favicon
  from http://www.xiconeditor.com/ (sized 64 x 64)
  and the apple icon
  from http://makeappicon.com/ (named AppIcon.appiconset/Icon-76@2x and sized 152 x 152)
- cannot see changed favicon. unless i change port
  how long does chrome cache the favicon ?
- spent a stupid amount of time writing humans.txt
- add intro
- looks very basic. no styling
- git sha: e1553907e41d56393343a9448e1055e2af944e76
- add CNAME to www.deepak-kannan.com
  dig www.deepak-kannan.com +nostats +nocomments +nocmd
  shows:
  ; <<>> DiG 9.8.3-P1 <<>> www.deepak-kannan.com +nostats +nocomments +nocmd
  ;; global options: +cmd
  ;www.deepak-kannan.com.		IN	A
  www.deepak-kannan.com.	1800	IN	CNAME	deepak.github.io.
  deepak.github.io.	3600	IN	CNAME	github.map.fastly.net.
  github.map.fastly.net.	10	IN	A	103.245.222.133
  configuring on namecheap as per
  http://davidensinger.com/2013/03/setting-the-dns-for-github-pages-on-namecheap/
  and https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider/
