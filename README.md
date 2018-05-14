# Pure CSS mime type/file type icon

So I was gonna sit down with my favorite image spriting service and glob together the set of file icons we use in a project. But it was nagging me to use images for this in the first place since we had just gotten rid of the glyphicons in favor of font awesome.

Figuring I could do it in CSS instead I set out and this is the result: http://css-file-type-icons.my-codeworks.com/

## Adjustments

The styles are tailored for the Source Code Pro font, since it's momo space, nice and we already had it in our project. You can switch it to whatever font you want but you'll need to adjust for the font to make the colored background box look nice.

### Adjusting background

Usually it's enough to switch font, fiddle with the font size so it fits horizontally, fiddle with the line height so the colored box covers the text vertically and then change the top offset to make sure it aligns ok on the background. You might have a situation where the colored background box gets a lot bigger than it has to, it happens ... This is when you have to make a choice. Change font, which is pretty ok as long as you choose a cross platform default, or start fiddling with the background...

I used a linear gradient during my initial testing (until I realized that Source Code Pro was behaving excellently without it) to make the parts of the background I didn't need transparent. It's easy enough and our app is internal and we can require people to run a recent version of Chrome when using it so that's nice. It might be a problem if you are building a public app, but I'll leave it up to thouse with the need to figure out a nice solution for it :)

### More fiddles

There are a lot more you could do with this, from niceties like borders and gradients and rounded corners to useful tweaks fo a particular situation, but this was enough for our needs, so I stoped there.

## Bye then!

If you use this anywhere or expand it for other uses I'd love to hear about it. But it's not required since I won't claim any rights for using the standards. Take it, keep it, modify it or rip it off. It's all good :)
