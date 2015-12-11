[Gitter et al 2014]: http://www.worldscientific.com/doi/abs/10.1142/9789814583220_0005
[Omics Integrator]: http://fraenkel.mit.edu/omicsintegrator
[msgsteiner]: http://areeweb.polito.it/ricerca/cmp/code/bpsteiner
[TCGA 2012]: http://www.nature.com/nature/journal/v490/n7418/full/nature11412.html
[Szklarczyk et al 2011]: http://nar.oxfordjournals.org/content/39/suppl_1/D561.long

# Multi-PCSF
An implementation of the Multi-PCSF algorithm described in [Gitter et al 2014].
This is an early, rough version of the PCSF code and is no longer under active
development.  Please see [Omics Integrator] for the current version of PCSF
from Ernest Fraenkel's lab.  However, Omics Integrator does not yet support the
multi-sample feature introduced by Multi-PCSF.  The Omics Integrator website
describes how to install the [msgsteiner] dependency, which is also required
by Multi-PCSF.

## Data
The breast cancer tumor sample data and protein-protein interaction network
data described in the Multi-PCSF manuscript are provided as an example
dataset.  If you use these data in a manuscript, cite [TCGA 2012] for
the breast cancer data and [Szklarczyk et al 2011] for the STRING
protein-protein interaction network.

## Developers
* Nurcan Tuncbag
* Anthony Gitter