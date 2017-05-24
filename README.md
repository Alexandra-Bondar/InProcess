# InProcess
1. Install python on https://www.python.org
2. Install cygwin32-64 or MinGW
  2.1 If cygwin32-64 -- install the curl, cygutils-extra, diffutils, gcc, gv, libX11-devel, libcurl-devel, libexpat-devel, make, 
  openssl-devel, sunrpc, xview-devel, and X-start-menu-icons packages(these are not installed by default in a minimal Cygwin installation).
  P.S. For MinGW read instruction in google.
  2.2 Install WFDB Software Package with wave. Download on physionet.org
3. Install libs: numpy+mkl, scipy for your system. Download on http://www.lfd.uci.edu/~gohlke/pythonlibs.
  P.S. For different IDE for python install the required libraries.
  3.1 If you use cygwin32-64 and python v3.4 or less, download pip3 instrument.
      Thank for this you can download the necessary libs for the python using the command
      $ pip3 install *lib*
