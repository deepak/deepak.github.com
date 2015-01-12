- cannot see the changed favicon ? 
  steps:
  - run a local server with 
    ruby -run -e httpd . -p 8000
  - see page
  - create new favicon
  - restart server
  - page still has old favicon
  - can see new favicon if server is started on new port
  Does browser cache favicon for a long time ?
  do not see request for favicon on Network panel as well
- why does html5 bootstrap not use ?
  <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />  
  
  