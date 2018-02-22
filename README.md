# ran

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
- [PythonEmbedInR](https://github.com/Sage-Bionetworks/PythonEmbedInR) - a modification of [PythonInR](https://bitbucket.org/Floooo/pythoninr) which embeds a private copy of Python, isolated from any Python installation that might be on the host system
