# docker-texlive-guitartex 
Minimal texlive alpine image including guitartex (gtx2tex)

* https://hub.docker.com/r/drpsychick/texlive-guitartex/
* based on https://github.com/phipsgabler/docker-texlive-minimal
* adds guitartex https://sourceforge.net/projects/guitartex/

## Convert gtx to pdf
docker run -it --rm -v $PWD:/data drpsychick/texlive-guitartex gtx2tex --output=pdf /data/mysong.gtx

## Issues
* [ ] thumbpdf throws errors with Ghostscript
