% Introduction to the Web
% Joseph Reagle

# Tim Berner-Lee's Three  Biggies

<span class="rightimage">![web](http://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/987822_95717228.jpg/320px-987822_95717228.jpg)</span>

1. URI/URL
2. HTTP
3. HTML

# URL: Uniform Resource Locator

**http://example.com/foo.html#section1**

The URL identifies a Web resource and includes a `scheme`, `authority` and a `path`.

# URL: scheme

**http**://example.com/new/foo.html#section1

* `http`
* `ftp`
* `mailto`
* `file`
* ...

# URL: authority

http://**example.com**/new/foo.html#section1

* hostname: `example.com`

# URL: path

http://example.com/**new/foo.html#section1**

* directory: `new`
* file: `foo.html`
* fragment: `#section1` (links to a specific element)

# HTTP: Hyper Text Transfer Protocol

<a title='By Gnome-fs-client.svg: David Vignoni Gnome-fs-server.svg: David Vignoni derivative work: Calimo (Gnome-fs-client.svg Gnome-fs-server.svg) [LGPL (www.gnu.org/licenses/lgpl.html)], via Wikimedia Commons' href='http://commons.wikimedia.org/wiki/File:Client-server-model.svg'><img width='500' alt='Client-server-model' src='http://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Client-server-model.svg/500px-Client-server-model.svg.png'/></a>

> * Your client sends a request.
> * The server sends a response.

You might request HTML, images, flash, etc.

# HTTP: cookies

Sometimes when the server responds, it asks you to hold a cookie for it, and then resend it back later.

<a title='By Tizio (Own work) [GFDL (www.gnu.org/copyleft/fdl.html) or CC-BY-SA-3.0 (www.creativecommons.org/licenses/by-sa/3.0/)], via Wikimedia Commons' href='http://commons.wikimedia.org/wiki/File:HTTP_cookie_exchange.svg'><img width='640' alt='HTTP cookie exchange' src='http://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/HTTP_cookie_exchange.svg/640px-HTTP_cookie_exchange.svg.png'/></a>

# HTML

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html .numberLines}
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
    "http://www.w3.org/TR/html4/loose.dtd">
<html>
 <head><title>The Document Title</title></head>
 <body>

  <h1 id="section1">This is heading</h1>

  <p> And this is a paragraph with a link to
  an <a href="http://example.com"> example</a>.</p>

 </body>
</html>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

# HTML: document type

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
    "http://www.w3.org/TR/html4/loose.dtd">
...
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This tells the browser what kind of document and version of HTML it is receiving -- there have been many!

# HTML: head and body

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}
...
<html>
 <head>...</head>
 <body>...</body>
</html>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

HTML documents have a **head**, with *metadata* about the document, and then a **body** full of *content*.

# HTML: head

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}
...
 <head>
  <title>The Document Title</title>
 </head>
...
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Includes *metadata*, such as the document's title.


# HTML: body

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}
...
 <body>

  <h1 id="section1">This is heading</h1>

  <p> And this is a paragraph with a link to an 
  <a href="http://example.com"> example</a>.</p>

 </body>
...
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

# Markdown -- digression

But wouldn't you rather type?

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.markdown}
# This is heading #

And this is a paragraph with a link 
to an [example](http://example.com).
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

# CSS: Cascading Style Sheets

CSS allows us to associate styles with HTML.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
h1 { color: white; background-color: orange }
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

And you can use the same sheet in many pages.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}
<head>
 <link rel="stylesheet" 
  href="http://example.com/css/style.css" 
  type="text/css" />
...
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

# JavaScript

JavaScript allows you to program elements of a Web page, making it dynamic.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
"http://www.w3.org/TR/html4/strict.dtd">
<html>
  <head><title>simple page</title></head>
  <body>
    <script type="text/javascript">
      document.write('Hello World!');
    </script>
  </body>
</html>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html}

