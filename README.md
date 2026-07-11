# einthovens_triangle

3-electrode Einthoven's triangle simulation.

Interactive Jupyter notebook that visualizes the heart's electrical vector projected
onto the three limb leads (I, II, III), assuming the heart is a single dipole at the
center of a homogeneous spherical torso.

## Run
```
pip install numpy matplotlib ipywidgets tqdm
jupyter notebook einthoven_triangle.ipynb
```

## Features
- Adjustable heart rate (HR)
- Simulated recording equipment: amplifier gain and noise level (independent of physiology)
- Cardiac condition presets: Normal Sinus Rhythm, Sinus Tachycardia/Bradycardia,
  Atrial Fibrillation, Myocardial Infarction, Left/Right Axis Deviation
- Live triangle view: heart vector + its projection onto each lead axis
- Lead I/II/III waveforms with animated or static (paused) time cursor
- Built-in check that Einthoven's law (II = I + III) holds for every condition

- <img width="647" height="317" alt="image" src="https://github.com/user-attachments/assets/c9130367-4436-479f-821f-286082c89251" />


For education only — not a diagnostic tool.
