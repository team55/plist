# <font color='red'><i>This project has moved to GitHub: <a href='https://github.com/3breadt/dd-plist'>https://github.com/3breadt/dd-plist</a></i></font> #


# dd-plist #

This library enables Java applications to work with [property lists](http://en.wikipedia.org/wiki/Property_List) in various formats.

You can parse existing property lists (e.g. those created by an iOS application) and work with the contents on any operating system.

The library also enables you to create your own property lists from scratch and store them in various formats.

The provided API mimics the Cocoa/NeXTSTEP API, granting access to the basic functions of classes like NSDictionary, NSData, etc.

_dd-plist_ has full support for the Android operating system. Consequently this library can be of great help when it comes to porting iOS apps to Android.

<table border='0'>
<tr>
<td valign='top'>
<h2>Supported formats</h2>
<table border='1px'>
<tr><th>Format</th><th>Read</th><th>Write</th></tr>
<tr><td>OS X / iOS XML</td><td>yes</td><td>yes</td></tr>
<tr><td>OS X / iOS Binary (v0)</td><td>yes</td><td>yes</td></tr>
<tr><td>OS X / iOS ASCII</td><td>yes</td><td>yes</td></tr>
<tr><td>GNUstep ASCII</td><td>yes</td><td>yes</td></tr>
</table>
</td>
<td><img src='http://upload.wikimedia.org/wikipedia/commons/c/c0/Blank.gif' width='32px' /></td>
<td valign='top'>
<h2>Download</h2>

The latest releases can be downloaded at the following locations:<br>
<ul>
<blockquote><li><a href='http://goo.gl/nsRGMC'>Google Drive</a></li>
<li><a href='http://goo.gl/ziwx2K'>Dropbox</a></li>
</ul>
</td>
</tr>
</table></blockquote>

## Maven support ##
If you use Maven and want to include the library into your project you can use the following dependency.

```
<dependency>
    <groupId>com.googlecode.plist</groupId>
    <artifactId>dd-plist</artifactId>
    <version>1.16</version> <!-- corresponds to r116 -->
</dependency>
```

# Help #

The API documentation is included in the download but can also be browsed online: [JavaDoc for com.dd.plist](http://dl.dropbox.com/u/2389669/plist/javadoc/index.html).

For examples on how to use this library please visit the [Examples page](http://code.google.com/p/plist/wiki/Examples).

When you encounter a bug please report it by on the  [issue tracker](http://code.google.com/p/plist/issues/list).

If you have further questions please post them in the [Discussion forum](http://groups.google.com/group/plist-discuss) on Google Groups.