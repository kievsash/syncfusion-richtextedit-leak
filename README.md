# TestApp

Checking if @syncfusion/ej2-angular-richtexteditor really has a leak

Here is reproduce: 
1. ng serve and go to localhost:4200
2. go back and forth to test page
3. With Edge Detached Elements DevTools tab (or ChromeDevTools Performance monitor) observe that Detached elements number is increasing

<img src="/syncfusion_richedit_leak.gif" width="800" height="400" />
