# DMPA
Open-source data for trajectory simulation of Drag-Modulated Plasma Aerocapture

## Background
This data is generated from the analytical plasma model of a magnetoshell interacting with a rarefied hypersonic atmospheric flow.  This data is generated for a flow of atomic hydrogen (H), making it applicable to conceptual DMPA trajectory simulations at Jupiter, Saturn, Uranus, and Neptune.  It accompanies [1], which can be found in this repository.  For more detail on the plasma model, see [2] and [3].

[1] _Kelly, C. L., & Little, J. M. (2021). Performance and Design Scaling of Magnetoshells for Outer Planet Drag-Modulated Plasma Aerocapture. In IEEE Aerospace Conference. Virtual Event. https://doi.org/10.1109/AERO50100.2021.9438387_

[2] _Little, J., & Kelly, C. L. (2020). Neutral flow interaction with a magnetic dipole plasma: I. Theory and scaling. Physics of Plasmas, 27(11), 113512. https://doi.org/10.1063/5.0024267_

[3] _Kelly, C. L., & Little, J. M. (2020). Neutral flow interaction with a magnetic dipole plasma: II. Global modeling. Physics of Plasmas, 27(11), 113511. https://doi.org/10.1063/5.0024268_

## How to use this data
The data is provided as a .csv file.  Each row contains a set of input parameters to the model and an output value of effective drag area.  The effective drag area is defined in Equation (3) of [1].  The freestream number density of H can be related to the atmospheric density using Equation (19) of [1].

If you have any questions about the use of this data or suggestions for improvement, contact Charlie Kelly at charleslawsonkelly@gmail.com.

## Change Log
*03/02/2021:* Initial commit

*05/26/2021:* Updated data file. Old data file (2021-03-02) is obsolete.

*04/23/2025:* Fixing some links and obsolete info.
