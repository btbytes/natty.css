# natty.css

all the css gains, all natty! 

[**demo page**](https://btbytes.github.io/natty.css/)

the idea behind `natty.css` is that you should be able to use just the right 
amount of CSS to style your webpage. What `natty.css` provides is:

1. default styling for most commonly used elements
2. use system fonts that are available on most popular operating systems
3. use sans-serif fonts
4. use `em` for defining width instead of `px`
5. this also prints well; "wywsiwyg" since the width is `43em.`

`natty.css` was inspired by [nat.org](https://nat.org),which has inspired many ai companies e.g: [Meta Superintelligence](https://www.meta.com/superintelligence/), and an earlier version of [ssi](https://ssi.inc) etc.


## how to use it

copy [natty.css](natty.css), **Read through the 12 lines** and delete everything
you don't need. you are not planning write any code? delete the `code` line.

```css
*{box-sizing:border-box;margin:0;padding:0;}
html{font-size:16px;line-height:1.6;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;background-color:#fdfdfd;color:#222;}
body{max-width:43rem;margin:2rem auto;padding:0 1rem;}
h1,h2,h3,h4,h5,h6{font-weight:600;margin:2rem 0 1rem;line-height:1.3;}
p{margin-bottom:1rem;}
a{color:#0066cc;text-decoration:none;}
a:hover{text-decoration:underline;}
img{max-width:100%;height:auto;display:block;margin:1rem 0;}
blockquote{border-left:4px solid #ccc;padding-left:1rem;margin:1.5rem 0;color:#555;font-style:italic;}
code{font-family:SFMono-Regular,Consolas,"Liberation Mono",Menlo,monospace;background:#f4f4f4;padding:0.2rem 0.4rem;border-radius:3px;}
ul,ol{padding-left:2rem;margin-bottom:1rem;}
hr{border:none;border-top:1px solid #ddd;margin:2rem 0;}
```
