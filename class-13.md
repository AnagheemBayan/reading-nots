# LOCAL STORAGE:

* userData: allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure


*  “HTML5 Storage” :is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. 


* HTML5 Storage: it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server


* The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

* the history of local storage hacks using third-party plugins:

storage limits are" 5 megabytes,” “QUOTA_EXCEEDED_ERR,” and “no.”  :


1. “5 megabytes” is how much storage space each origin gets by default. 

1. “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes. 

1.  “No”  is the answer to the next obvious question, “Can I ask the user for more storage space?” At time of writing (February 2011), no browser supports any mechanism for web developers to request more storage space

![storage](https://techglimpse.com/wp-content/uploads/2013/05/Pass-LocalStorage-data-to-PHP-using-jQuery.jpeg)
