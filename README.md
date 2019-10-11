# DistributedProcessing
PNAS Distributed Processing for Movement Signaling
Data files for “Distributed Processing of Movement Signaling”

Two Matlab “.mat” files, one for each monkey contain organized data from 10 different recording sessions.  Each file consists of a structure, MonkeySdata or MonkeyIdata, which has field names of  force, mforce, displacement, mdisplacement, fr, and mfr.   The “m” if signifies mean-  the repetitions to each of the 16 conditions were averaged together.  The “force” field contains 3D force data collected from the force sensor below the handle.  Dimension 2 is along the track, Dimension 1, is toward/away from the monkey, and Dimension 3 is up and down.  The data are arranged in 10-second bins and the handle release took place in bin 7.  The force data are arranged as 16 experimental conditions x number of repetitions x 3 force dimensions x number of bins.  The mforce data are 16 x   3 x bins.  The displacement data are 16 x number of repetitions x number of bins,  mdisplacement is 16 x number of bins.  The firing rate (as described in the text), fr, is 16 x number of repetitions x number of isolated units x number of bins.

The mean data were used for Figures 6 and 7.  The force generated at release came from the maximum force for that condition taken along dimension 2.  The displacement came from bin 70 of the mean displacement data.
