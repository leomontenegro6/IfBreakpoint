# If Bootstrap 4 Breakpoint do something
Detect Bootstrap 4 breakpoints to run conditional scripts and functions

Bootstrap 4
`<script src='https://cdn.rawgit.com/JacobLett/IfBreakpoint/e9fcd4fd/if-b4-breakpoint.min.js'></script>`

Bootstrap 3
`<script src='https://cdn.rawgit.com/JacobLett/IfBreakpoint/e9fcd4fd/if-b3-breakpoint.min.js'></script>`


### Are you extra-small?
```
// update onload
$(document).ready(function(){
  // update onload
  $("h2").text( breakpoint ); 
  
  if ( xs == true ) { 
    alert("mobile first");
  }

  // Update on window resize
  $( window ).resize( function(){
    $("h2").text( breakpoint ); 
  }); 

});
```
