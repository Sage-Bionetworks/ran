# This repository formerly hosted Sage Bionetworks' R Archive Network - it is now deprecated in favor of http://ran.synapse.org/

![Sage Bionetworks logo](sage-bionetworks.png)

# Sage Bionetworks R Archive Network

This is the Sage Bionetworks R Archive Network (RAN) - a CRAN-like repository for R packages published by Sage Bionetworks.

Packages in this RAN can be installed or upgraded using the standard `install.packages()` command by adding this RAN to the repository list, e.g.:

```
install.packages("synapser", repos=c("https://sage-bionetworks.github.io/ran", "http://cran.fhcrc.org"))
```

Alternatively, edit your `~/.Rprofile` and configure your default repositories:

```
options(repos=c("https://sage-bionetworks.github.io/ran", "http://cran.fhcrc.org"))
```

after which you may run `install.packages()`.

# Available packages

- [synapser](https://github.com/Sage-Bionetworks/synapser) - an interface to [Synapse](https://www.synapse.org), a collaborative workspace for reproducible data intensive research projects
- [synapserutils](https://github.com/Sage-Bionetworks/synapserutils) - a package that provides a set of utility functions, built on top of the synapser package.
- [PythonEmbedInR](https://github.com/Sage-Bionetworks/PythonEmbedInR) - a modification of [PythonInR](https://bitbucket.org/Floooo/pythoninr) which embeds a private copy of Python, isolated from any Python installation that might be on the host system
