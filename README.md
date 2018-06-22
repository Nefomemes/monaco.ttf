# monaco.ttf

The original monaco.ttf improved: add some special characters (which are from "DejaVu Sans Mono")

In my work environment, I need connect to Linux system from Windows system remotely using SecureCRT or Putty, and edit files using VIM tools. So I need one beautiful font in SecureCRT / Putty.

In windows system, there are some original fonts are beautiful, for exemple "Consolas", but they can't support some special characters, for example: ▸, ↪, ⌴. Because they are original fonts in my Windows, I don't want to modify them.

I get "Monaco" from the web. It is tiny and beautiful. But it also can't support those special characters.

So I add the characters by myself and share it.

## CDN
You can use rawgit.com as a CDN:
https://rawgit.com/todylu/monaco.ttf/master/monaco.ttf

## Web usage
Copy this code into the <head> section of your HTML document:
```html
<link href="https://rawgit.com/todylu/monaco.ttf/master/monaco.ttf" rel="stylesheet">
```
  
Then in your CSS:
```css
font-family: 'Monaco', monospace;
```
  
  