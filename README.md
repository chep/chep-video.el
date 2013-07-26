chep-video.el
=============

Allows you to play videos inside emacs.

chep-video-el  ---  allows you to play videos in emacs

Filname: chep-video-el
Description: allows you to play videos in emacs
Author: Cédric Chépied <cedric.chepied@gmail.com>
Maintainer: Cédric Chépied
Copyright (C) 2013, Cédric Chépied
Last updated: Th Jul 25th
    By Cédric Chépied
    Update 1
Keywords: video mplayer
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

Commentary:

The way we play video is ugly but works: mplayer is called with -vo png
so it plays sound and extracts video frames in /tmp/chep-video.d as png
files. A timer is set in emacs to periodically display and delete images.

Keys and interactive functions:
chep-video-play:                           start playing a video
chep-video-stop:                           stop current playing video
chep-video-playPause (space):              toggle play pause state
chep-video-forward (right):                go 10 sec forward
chep-video-backward (left):                go 10 sec backward
chep-video-forward-long (up):              go 1 min forward
chep-video-backward-long (down):           go 1 min backward
chep-video-forward-long-long (page up):    go 10 min forward
chep-video-backward-long-long (page down): go 10 min backward



;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3, or (at your option)
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; see the file COPYING.  If not, write to
the Free Software Foundation, Inc., 51 Franklin Street, Fifth
Floor, Boston, MA 02110-1301, USA.

Copyright Cédric Chépied 2013
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
