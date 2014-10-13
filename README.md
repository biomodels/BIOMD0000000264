

Akt pathway model with EGFR inhibitor

made by Kazuhiro A. Fujita.

This is the Akt pathway model with an EGFR inhibitor described in:  
**Decoupling of receptor and downstream signals in the Akt pathway by its low-pass filter characteristics.**   
Fujita KA, Toyoshima Y, Uda S, Ozaki Y, Kubota H, and Kuroda S. _Sci Signal._
2010 Jul 27;3(132):ra56. PMID:
[20664065](http://www.ncbi.nlm.nih.gov/pubmed/20664065) ; DOI:
[10.1126/scisignal.2000810](http://dx.doi.org/10.1126/scisignal.2000810)  
Abstract:  
In cellular signal transduction, the information in an external stimulus is
encoded in temporal patterns in the activities of signaling molecules; for
example, pulses of a stimulus may produce an increasing response or may
produce pulsatile responses in the signaling molecules. Here, we show how the
Akt pathway, which is involved in cell growth, specifically transmits temporal
information contained in upstream signals to downstream effectors. We modeled
the epidermal growth factor (EGF)–dependent Akt pathway in PC12 cells on the
basis of experimental results. We obtained counterintuitive results indicating
that the sizes of the peak amplitudes of receptor and downstream effector
phosphorylation were decoupled; weak, sustained EGF receptor (EGFR)
phosphorylation, rather than strong, transient phosphorylation, strongly
induced phosphorylation of the ribosomal protein S6, a molecule downstream of
Akt. Using frequency response analysis, we found that a three-component Akt
pathway exhibited the property of a low-pass filter and that this property
could explain decoupling of the peak amplitudes of receptor phosphorylation
and that of downstream effectors. Furthermore, we found that lapatinib, an
EGFR inhibitor used as an anticancer drug, converted strong, transient Akt
phosphorylation into weak, sustained Akt phosphorylation, and, because of the
low-pass filter characteristics of the Akt pathway, this led to stronger S6
phosphorylation than occurred in the absence of the inhibitor. Thus, an EGFR
inhibitor can potentially act as a downstream activator of some effectors.

The different versions of input, step, pulse and ramp, can be simulated using
the parameters _EGF_conc_pulse_ , _EGF_conc_step_ and _EGF_conc_ramp_ .
Depending on which one is set unequal to 0, either a continous pulse with
value _EGF_conc_pulse_ , a 60 second step with _EGF_conc_step_ or a signal
increasing from 0 to _EGF_conc_pulse_ over a time periode of 3600 seconds are
used as input. In case more than one parameter are set to values greater than
0 these input profiles are added to each other. The pulse time and the time
over which the ramp input increases can be set by _pulse_time_ and _ramp_time_
.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)

