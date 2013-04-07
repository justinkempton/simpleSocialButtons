simpleSocialButtons
===================

I got annoyed with trying to setup social button for my sites. 
They all use different code styles and practices to load their scripts on the page. This make me have to load
their code into my source all over my page and it is esthetically irritating to do that. I thought, maybe I could
write one script that would load them all. And, hey, while I'm at it, why not give it a refresh. So that is what I 
did. 

It requires jQuery. But it could be easily ported to some other library (if you prefer). 
Also, needs to know the browser, for ie9. Current jQuery support for the browser object is depricated (but I still
like it) and add it back to jquery. Not required, but for IE9 it will not behave nice.

The cool thing is you can refresh the social buttons easily.

Using Chrome you can type in socialBar in console (or the name of the instance)

it should output all the methods:

socialBar
Object {refreshAll: function}
refreshAll: function (url, newTitle) {
__proto__: Object

so, to refresh you would do this socialBar.refreshAll("http://thenewUrl.com", "new title")

bamn! that's it. Please enjoy and add stuff like Google if you want.
