| Toolbox Name                               | dmod | d2d | PESTO                                                                   | Copasi |
|--------------------------------------------|------|-----|-------------------------------------------------------------------------|--------|
| *Call to sampling function*                | tbd  | tbd | getParameterSamples()                                                   | tbd    |
|                                            |      |     |                                                                         |        |
| **MCMC, single chain**                     |      |     |                                                                         |        |
| *Metropolis-Hastings, Adaptive Metropolis* | tbd  | tbd | options.MCMC.samplingAlgorithm   = PT; options.MCMC.PT.nTemps = 1;      | tbd    |
| *Delayed rejection*                        | tbd  | tbd | options.MCMC.samplingAlgorithm   = DRAM; (needs DRAM toolbox)           | tbd    |
| *(S)MMALA*                                 | tbd  | tbd | options.MCMC.samplingAlgorithm   = MALA;                                | tbd    |
| *Hamilton Monte Carlo*                     | tbd  | tbd | no                                                                      | tbd    |
|                                            |      |     |                                                                         |        |
| **MCMC, multi chain**                      |      |     |                                                                         |        |
| *Parallel tempering, adaptive Metropolis*  | tbd  | tbd | options.MCMC.samplingAlgorithm   = PT; options.MCMC.PT.nTemps = ...;    | tbd    |
| *Parallel hierarchical Sampling*           | tbd  | tbd | options.MCMC.samplingAlgorithm   = PHS; options.MCMC.PHS.nChains = ...; | tbd    |
| *Parallel tempering (S)MMALA*              | tbd  | tbd | no                                                                      | tbd    |
