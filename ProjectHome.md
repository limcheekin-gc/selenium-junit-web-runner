It is Selenium Test Driver Grails application with easyb (http://easyb.org/) -> Selenium RC (http://seleniumhq.org/projects/remote-control/) -> JUnit Web Runner Application (http://code.google.com/p/junit-web-runner/), e.g. Live Demo of JUnit Web Runner (http://junit-web-runner.appspot.com/).

# Sample Usage #
```
grails test-app unit:easyb -Dhost=localhost -Dport=4444 -Dbrowser=*googlechrome -Durl=http://junit-web-runner.appspot.com
```