# Outline

1. Cosmic Ray Astrophysics
    Can go one of two ways:
    1. Measurements into interpretation (Frank's preference)
        1. Energy spectrum
        2. Mass Composition
        3. Anisotropy
        4. Sources and Acceleration Mechanisms
        5. Propogation Effects
    2. Interpretaion/Phenomenology into measurements
        1. Sources and Acceleration Mechanisms
        2. Propogation Effects
        3. Anisotropy
        4. Energy Spectrum
        5. Mass Composition
2. Cosmic Ray Air Showers (?)
    1. Heitler-Matthews Model of Air Showers
    2. Hadronic Cascade
        1. Muonic Component
    3. Electromagnetic Cascade
        1. Radio Emission from Cosmic Ray Air Showers (Overleaf notes)
    4. Air Shower Universality (for better understanding of Ch. 4)
        1. Shower-to-shower Fluctuations
        2. Longitudinal Profile -> He outlier (SKA proceeding)
    5. Attenuation in atmosphere -> Used as motivation for including sec(zen) and r in NN
    6. Uncertainties from Hadronic Interaction Models
3. The Pierre Auger Observatory
    1. Sufrace Detecors
    2. Fluorescence Detectors
    3. AERA
    4. Underground Muon Detectors
    5. Reconstruction of Events
    6. AugerPrime (mention UUB w/ trigger out for ARISE)
4. Combinations of Air-Shower Observables for Improved Primary Mass Sensitivity
    1. Simulation Dataset Overview -> Focus on Auger (simulations with updated hadronic interaction models)
    2. Modeling Observables and their Reconstruction Accuracy
        1. Fitting the Longitudinal Profile of Air Showers
    3. Principal Component Analysis to Model Mass Sensitivity
    4. Gradient Boosted Decision Trees to Improve Mass Sensitivity
        1. Containment plots
5. Neural Network Based Reconstructions of a Muon Observable
    1. Description of Past Analysis
    2. Network Architecture
    3. Data/Simulation Cuts
    4. Training + Testing Results, Testing for Biases
    5. Application to Reconstructed Surface Detector Data
    6. Crosschecks that Orazio and Juan Miguel did
        1. Train only on protons
        2. Train without some variables
        3. Inclusion of atmosphere/season (?)
        4. Plots of bias (S_DNN - S_MC) and resolution sigma(S_DNN - S_MC) as functions of E_MC, sec(zen), and S_tot
        5. Direct comparison of simulated muonic PMT signal per bin with prediction from NN
        6. Crosschecks with Underground Muon Detector Reconstructions (?)
        7. Crosschecks with Margita's NN (?)
6. Combined Analysis of Muon and Electromagnetic Reconstructions
    1. AERA Shower maximum reconstructions on the SD energy scale (Bjarni work)
        1. Describe Dataset (not full details of analysis...)
        2. Extension until the end of Auger Phase I (?)
    2. Reconstructing the absolute EM energy from AERA
        1. Radio measures an EM cascade on the absolute level -> prefer this because it is purely EM measurement
        2. Again, no need to describe full analysis...
    3. Muon and Shower Maximum Reconstructions with an EM Energy
        1. Comparison of ln(A) Plots (avg. and sigma)
    4. Combination of Muon and Shower Maximum Observables into a Single Observable (?)
    5. Discussion/Interpretation
7. Future Prospects: SKALA Radio Antennas at Auger
    1. IceCube Gen2 Prototype Station at the Pierre Auger Observatory
        1. Deployment
        2. Galactic Noise Observation
        3. First Data Reconstructions and Comparision to Auger Reconstructions
    2. ARISE: Auger Radio Infill SKALA Extension
        1. Science Potential
        2. Deployment
        3. Outlook
8. Conclusion

9. Appendices
    1. Auger Surface Detector PMT Timing Differences
    2. Prototype Layered Surface Detector Calibration