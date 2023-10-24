# TCC_Physics_Webpage

[TCC Physics Webpage](website/index.html)


-------------------------------------------

## Notes for compiling Website

Use the Quarto render command to generate website

```
quarto render
```

Then copy all of the contents from "_site/" directory into
the "website/" directory.

```
cp -r _site/* website/
```

Finally sync with Github to update the live page version

```
git add .
git commit -m "add your comment here about changes"
git push
```

