# Copyright (C) 2014-2017 AscEmu Team <http://www.ascemu.org>

set(PATH_PREFIX Server/Warden)

set(SRC_SERVER_WARDEN_FILES
   ${PATH_PREFIX}/SpeedDetector.cpp
   ${PATH_PREFIX}/SpeedDetector.h
)

source_group(Server\\Warden FILES ${SRC_SERVER_WARDEN_FILES})
unset(PATH_PREFIX)
