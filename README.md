cdrip-tools
===========

arverify.py
  Accuraterip verifier that supports multiple lossless formats via
  sox and ffmpeg.

  Supports offset detection and both accuraterip v1 and v2.

  Additionally supports specifying additional pregap samples
  as well as data track length in order to get the correct disc id
  from the accuraterip database.

fixoffset.py
  Companion program to fix the offset of a rip.

splitaudio.c
  small libsdnfile C99 program to split raw audio read from stdin

ckcdda.c
  adapted from https://github.com/jonls/accuraterip-tools)

Dependencies:
  sox ffmpeg libsndfile
Optional:
  metaflac libsox-fmt-ffmpeg

License:
  GPLv3

Ubuntu 12.04:
  aptitude install sox ffmpeg libsndfile1-dev flac libsox-fmt-ffmpeg