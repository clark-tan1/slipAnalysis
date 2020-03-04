# slipAnalysis
Calculates and plots schmid factors, plane traces and opening angles in a deformed sample
Load your grain file in .txt format from TSL OIM or other
Pick a grain and a lattice (e.g. BCC), the programm will:
  - compute all Schmid factors, plot and save them
  - compute all plane traces, plot and save them
  - compute all opening angles in the reference frame of the slip band, and save them
Download both files and change the path to your grain file. You can also change the heading and infer directly your Euler angles.
Conventions: loading direction = horizontal (message me if you'd like me to make it a parameter of the code)
Euler angles = Bunge's convention (angles are all in degrees, though there's a function in crystallography.py you can change to convert them if needed, message me if you'd like this to be a parameter in the code)

## examples
Here's an example of the code's output, for a grain of Euler angles (194.3,83.2,68.1) in a BCC lattice