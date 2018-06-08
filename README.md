# Sublime Text 3 configuration

## Package Control

* Open the console with `` Ctrl+` ``
* Paste in the following:

```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

From here on out, use [Package Control](https://sublime.wbond.net/browse) to install **everything**. `⌘`+`Shift`+`P`, then type `Install Package` to get a list of installable packages you can livesearch through. Watch the Status Bar for installation progress.

## Theme

Select `Adaptive` theme by pressing `⌘`+`Shift`+`P`, then `UI: Select Theme`.

## Color scheme

Select `Monokai` color scheme by pressing `⌘`+`Shift`+`P`, then `UI: Select Color Scheme`.

## Packages

* `GitGutter` tracks line changes in the gutter.
