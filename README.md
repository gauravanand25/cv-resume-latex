# Dependencies

- Fonts
  Install Fontin which can be downloaded from here[https://www.exljbris.com/fontin.html].
  Put it inside /usr/share/fonts/fontin

# Instructions

- The following should work proviso you have all the dependencies listed above.
  
```
$ xelatex cv.tex

# or get [tectonic](https://tectonic-typesetting.github.io/en-US/install.html)

$ tectonic cv.tex
```

- I like to use pdf2htmlEX to create an HTML version of the CV for my [blog](https://gauravanand25.github.io/cv).
  
```
    pdf2htmlEX --process-outline 0 --zoom 1.6 cv.pdf
```

# Attribution

This template takes elements from the Alessandro Plasmati's resume template and further work for Srijan Shetty. I have made minimal changes.

