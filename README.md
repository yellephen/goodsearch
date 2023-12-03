This lets you search a term and it'll open new tabs, each with a google search limited to the one of the chosen domains. At the moment these are
var domains = [
"github.io", 
"medium.com",
"reddit.com",
"microsoft.com",
"twitter.com",
"hacklido.com/blog/"
];

It's a static site with some JavaScript so you can just put it in in a folder in /var/www/html.

Before it works in your browser, probably have to set an exception to allow popups.
