The dataset used in this project focuses on the effect of Parkinson's disease (PD) on speech. It consists of multiple biomedical voice measurements taken from people who have PD and people who don’t have PD. The measurements taken are:
    MDVP:Fo(Hz) - Average vocal fundamental frequency 
    MDVP:Fhi(Hz) - Maximum vocal fundamental frequency 
    MDVP:Flo(Hz) - Minimum vocal fundamental frequency 
    MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency 
    MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in    amplitude 
    NHR,HNR - Two measures of ratio of noise to tonal components in the voice 
    status - Health status of the subject (one) - Parkinson's, (zero) - healthy 
    RPDE,D2 - Two nonlinear dynamical complexity measures 
    DFA - Signal fractal scaling exponent 
    spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation 
    
The aim of this project was to investigate which pairs of measurements could be used to best predict if a person has PD or not using a K-nearest neighbours analysis (KNN).

To run:
    1. Open the python notebook file (Code_ZSH.ipnyb) on Jupyter notebook and run the given code.
    2. The existing code investigates five measurement pair combinations. Additional different measurement pair combinations can be tested using the code for KNN analysis by replacing the measurement pair names to those being tested.





