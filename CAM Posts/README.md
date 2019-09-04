CPS files are the postprocessors used with your Autodesk CAM software.

# Ronald:
  Modified roland_rml.cps post from Autodesk HSM Library. Only known working method of control.
  Postprocess in millimeters only!
  Manual NC works only using "Pass Through" operation subtype.
  For rotary jig control, angles can be indexed using Manual NC and command format
    ;!ZEA#.#;
    where #.# is your decimal degree angle.

# Tormach:
  Path Pilot post downloaded from Autodesk HSM Library. Professional equipment; no jank.

# ForrestScientific:
  Unpublished post given to us upon request, required to run machine with Autodesk software.
