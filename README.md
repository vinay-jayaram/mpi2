# MPI_beamertheme
A repo where people can help us set up a good beamer theme for the MPI IS (or other institutes, really whatever. The help would just be nice)

# License

The files logo_notext.pdf and logo_white.pdf are copyright (C) Max Planck Society. Do not download or use them in any way without permission.

# Usage

This repo contains a Beamer theme in 16:9 with a variety of options. The inner and outer theme describe the title page and header/footer/frametitle, with some convenience environments and re-definitions in file beamerthemempi2.sty. Examples are:

1. the `imframe` environment, which gives you a slide with a picture in the background (NOTE: you have to get your picture the right size yourself)
```
\begin{imframe}{image filename}

\end{imframe}

```
One thing I'd like to do is add an option for an overlay of semi-transparent MPG_green

2. the `solidframe` environment, which inverts the color scheme (roughly speaking)

3. The item marker and enumerate markers have been altered