#!/bin/bash
# $Id: CMakeLists.txt 1997 2016-10-17 16:22:42Z stephane $

FILE ( GLOB SCRIPTS *.sh )
LIST ( SORT SCRIPTS )

INSTALL ( PROGRAMS ${SCRIPTS} DESTINATION bin )
