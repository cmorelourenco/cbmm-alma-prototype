# CBMM ALMA prototype — deploy folder

`index.html` is the whole prototype in one file (every page, script, style and
image inlined). Host this folder anywhere that serves static files and the
prototype works at that address with no sign-in for viewers.

Rebuild after changes:  python3 build_share.py && cp share/cbmm-alma-prototype.html deploy/index.html
