# Material for NEST tutorial at BRANDY 2025

This material is publicly available at https://github.com/jhnnsnk/BRANDY2025_NEST.

| :memo:  Please fork this repository and then clone the fork if you want to push your changes to GitHub. |
| --- |
| :zap:  **Do not clone this repository directly.** |

**BRANDY BRAin Dynamics academY EBRAINS-Italy school**  
Sardinia, Italy  
4-11 September 2025   
https://brandy.ebrains-italy.eu

Presented by Johanna Senk (j.senk@sussex.ac.uk) and Ariel Shmilli (a.shmilli@sussex.ac.uk).  
This tutorial gives an introduction and demonstration into modeling of the dynamics of spiking neuronal networks, explaining graphical as well as programmatic approaches on the basis of the simulation code NEST. Examples and exercises make use of the graphical user interface **NEST Desktop** and Jupyter notebooks for **PyNEST** and **NESTML** code using the EBRAINS infrastructure.

For documentation and background reading:
- NEST in general: https://nest-simulator.readthedocs.io
- NEST Desktop: https://nest-desktop.readthedocs.io
- NESTML: https://nestml.readthedocs.io 

## EBRAINS

Go to https://www.ebrains.eu and create an EBRAINS account with your institutional email address.
If this does not work, contact the presenter and ask for a guest account.

## NEST Desktop

1. Go to https://nest-desktop.apps.hbp.eu. The Chrome browser usually works best.
1. Sign in with your EBRAINS account.
1. Select `NEST` as simulation tool.
1. In the `Frontend` section on the right, you can either load an existing project or start a new one. If you want to load the project prepared in this repository, click on the `Import` icon next to `Store list`.
1. Choose `Import from URL` and paste the link to the `Raw` version of `1_NESTDesktop2PyNEST/balanced_network.json`.  
   (for convenience: https://raw.githubusercontent.com/jhnnsnk/BRANDY2025_NEST/refs/heads/main/1_NESTDesktop2PyNEST/balanced_network.json)  
   Press `FETCH`, select the file `Balanced network`, and `IMPORT SELECTED`.
1. Now the project `Balanced networks` appears under `Existing projects` and can be opened.

### How NEST Desktop stores models

- NEST Desktop stores models as *cookies in your browser*
- Models will disappear when your browser cleans up cookies.

| :zap: Always **export your models** to disk for safe storage. |
|---------------------------------------------------------------|

- And vice versa, if you experience any issues with the simulation, deleting cookies often helps.

## Working with the PyNEST examples on EBRAINS

| :zap:  Material not pushed from EBRAINS back to GitHub may disappear overnight. |
| --- |

1. **Fork this repository**.
1. Go to https://lab.ebrains.eu and sign in.
1. Choose Jülich Supercomputing Center (JSC).
1. Upon "Start Server", EBRAINS spins up a virtual machine (VM) for you with 2 GB RAM.
1. You have a file browser to your left.
   - Top level is your **local home** on the VM. It exists as long as the VM.
   - **Do not use** `shared` (contains long-term storage but needs a *Collab* and is not suitable for storing Git repos) or `drive` (deprecated).
1. **Clone your fork** of the `BRANDY2025_NEST` repository under the "Git" logo in the left margin (use the HTTPS version: https://github.com/jhnnsnk/BRANDY2025_NEST.git ). There you also find tools for managing Git. For pushing to your repository, you will need to set up an access token, see https://github.com/settings/tokens. 
1. **Always commit and push at the end of a session.**
1. EBRAINS will from time to time shut down inactive VMs. **Any material in your VM home directory will then be lost**—remember to push!
1. You can shut down a server yourself via `File > Hub Control Panel`. The entire VM including your home on the VM is deleted then.
   
### Direct access to the execution sites

If you remember on which site your VM is running, you can contact it directly:

- https://lab.jsc.ebrains.eu
