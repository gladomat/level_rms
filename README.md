# level_rms
A python script that adjusts RMS values auf WAV files.

This function is based (pretty much 1-1) on the matlab script written by Daniel McCloy (drmccloy@uw.edu) which he LICENSED UNDER A CREATIVE COMMONS ATTRIBUTION 3.0 LICENSE: http://creativecommons.org/licenses/by/3.0/

It normalizes a set of files to all have the same RMS amplitude. Target amplitude is either (1) matched to that of an existing wav file that you specify, or (2) the maximum possible RMS that still avoids clipping.

This script uses scipy.wavefile.read() which can only read 16-bit wave files.
