# Printing

This is how to print these pesky speaker note cards in my HP LaserJet with the center
manual feed:

    lpr -PBobMP -o landscape -o position=center -o media=Custom.3x5in filename.ps

For page ranges, try this:

    lpr -PBobMP -o page-ranges=1-4,7,9,10-12 -o filename.ps


https://www.cups.org/doc/options.html
