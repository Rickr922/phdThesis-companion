# Non-Iterative Numerical Simulation Techniques for Nonlinear String Vibration in Musical Acoustics

This repository serves as a companion page for my PhD dissertation in Mechanics and Advanced Engineering Sciences at the University of Bologna. It contains audiovisual examples corresponding to various chapters of the thesis. Note that all the audio files represent velocity instead of displacement, i.e. the derivative of the displacement.

## Geometric (Chapter 4)
Includes audio files related to Figures 4.6 and 4.7, along with the figures themselves. As in the figures, the suffix:
- `noSAV` indicates that the model was solved with a linearly implicit solver.
- `SAV_noConstr` refers to SAV without constraint.
- `SAV_withConstr` refers to SAV with the constraint applied.

## Collisions (Chapter 5)
Contains three audio files related to Figures 5.8–5.11, along with the figures. The suffix:
- `noConstr` indicates that no constraint was applied.
- `withConstr_thetaPr05` refers to the case shown in Figure 5.9.
- `withConstr_thetaPr0` corresponds to the case in Figure 5.11.

Additionally, the video `hammerStringCollision` is an animation illustrating a hammer-string collision, from which Figure 5.6 is taken.

## Guitar (Chapter 7, First Paper)
Stores various audio examples from the first paper presented in this chapter, all obtained using the model described in the paper:
- `KConly_Audio`, `KCfretboard_Audio`, and `Tap_Audio` correspond to panels (a), (b), and (c) of Figure 3 in the paper, respectively. The related figures are also included.
- `Tap_Video` is a real-time animation of the energy behavior shown in Figure 2, corresponding to the `Tap` sound and figure.

## EfficientBowedString (Chapter 6)
Links to the companion repository for the paper *Efficient Simulation of the Bowed String in Modal Form*, from which much of Chapter 6 is derived. This repository contains audio examples and MATLAB code, with file descriptions provided inside.

## yaybahar-nit (Chapter 7, Second Paper)
Links to the companion repository for the second paper presented in Chapter 7, where file descriptions can be found.
