Show Q
------
ShowQ is audio / MIDI trigger software for theatre productions.


Requirements
------------
The software requirements for build and runtime are as follows:

    - python (required for build only for waf)
        http://www.python.org/
    - gtkmm
        http://www.gtkmm.org
    - libxml++
        http://libxmlplusplus.sourceforge.net/
    - Jack Audio Connection Kit
        http://jackaudio.org/
    - ALSA
        http://www.alsa-project.org/
    - sndfile
        http://www.mega-nerd.com/libsndfile/
    - vorbisfile
        http://www.vorbis.com/
    - samplerate
        http://www.mega-nerd.com/SRC/
    - libboost (headers required for build only)
        www.boost.org

Installation
------------
The installation procedure is as follows:

    ./waf configure
    ./waf

and as root:

    ./waf install

to install to /usr rather than /usr/local:

    ./waf --prefix=/usr install

License
-------
Show Q is distributed under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2 of the
License, or (at your option) any later version.  A copy of this license
can be found in the file COPYING included with the source code of this
program.

Ideas, questions, patches and bug reports
-----------------------------------------
http://www.github.com/evandelisle/showq

--
Errol van-de-l'Isle
