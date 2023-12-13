***Exception-PropagatioHandlingn-00***
<br>
**This repo talks about how to handle exceptions using custom policy. In this policy we are capturing error using on error continue**
<br>
**set-payload from custom policy will be ignored once error will occur in application it will directly go into on error continue block of custom policy**
<br>
**The response which is set in http-transform:set-response will get printed**
<br>
**So, overall flow execution will be like. 1. Logger from custom policy, 2. flows/loggers will be covered of application before the error has happened. Then on error cntinue block of custom policy will be printed.**
