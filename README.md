# MyStats
Some statistics-related code I've put together, some of which may duplicate J standard libraries
The routines include here are the following.
NB.* redoLnLabels: replace ln values w/original values in x labels of ln plot.
NB.* norm01: normalize series to map from zero to one.
NB.* covariance: Calculate covariance of two vectors -> covariance (atom).
NB.* autoCorr: auto-correlation of y for lag of x.
NB.* wmean: weighted mean of y weighted by x
NB.* wdev: weighted deviation of y weighted by x
NB.* wssdev: weighted sum of squares of deviation of y weighted by x
NB.* wvar: weighted variance of y weighted by x
NB.* wstddev: weighted standard deviation of y weighted by x
NB.* shapedRand: generate random numbers from distribution shaped by parameters.
NB.* intraclassCorrelation: calc intraclass correlation given mat of classes by items.
NB.* collectFncStats: collect statistics on results of function.
NB.* boxMueller: Box-Mueller (polar) method to gen samples of normal dist.
NB.* bMcore: core calculation to generate standard normal samples.
NB.* winsorizeAtVal: winsorize at specified (low, high) value.
NB.* winsorizeAtPct: winsorize at percent from bottom and top; 0->none.
NB.* winsorizeAt: winsorize top and bottom at xth highest/lowest observation.
NB.* usus: my usual descriptive stats: min, max, mean, stddev
NB.* bivariate_normal: random numbers normally distributed along 2 dimensions
NB.* normalrand: choose y normally distributed random numbers
NB.* minPtn: partition into x parts numeric vector y to min diffs of sums.
NB.* parameterizedMats: create npt integer matrixes according to 3 parameters.
NB.* myMatInv: cover for %.-> return code;<answer or _.
NB.* myCholeski: cover for Choleski decomposition->return code;<answer or _.
NB.* powerMean: generalized mean: for N&powerMean for N: _1: harmonic; 1:
NB.* normSeries: normalize numeric series so it has same mean and stddev as
NB.* AllCombos: make mat of all possible distinct y things taken x at a time.
NB.* rmlt: remove elements of y < x
NB.* tr: (matrix) trace function
NB.* medianAbsDev: median absolute deviation.
NB.* setPlotColors: set plot colors to emphasize contrast between adjacent
NB.* genSD: generalize stddev to use arb exponent instead of 2.
NB.* plotHistoMulti: given title >0{x, plot 20 bucket histogram of multiple
NB.* histoDistrib: histogram distribution: count how many numbers in vector y
NB.* upperTri: return upper triangle of square mat y.
NB.* lowerTri: return lower triangle of square mat y.
NB.* corrStbl: correlation (more stable than "corr" from statfns.ijs).
NB.* crosscorrMat: build cross-correlation matrix between rows of 2 input mats.
NB.* corrMat: build correlation matrix of rows of input matrix.
NB.* SpearmanRho: Spearman's rank correlation coefficient for 2 rows of mat of
NB.* MAD: Mean Absolute Deviation
NB.* HurstExponent: calculate Hurst exponent (rescaled range analysis)
NB.* ret1p: 1-period return
NB.* KendallTau: calculate Kendalls tau (rank correlation coefficient) given
NB.* winsorize: cap high and low outliers of vec y at x (low, high) level(s).
NB.* fr: Nub frequencies
NB.* frtab: Frequency table
NB.* ptPairUp: pair up numbers x apart->complex nums for point (dot) plot.
NB.* mstat: xth moment of y
NB.* beta1: skewness
NB.* beta2: kurtosis (A&S)
NB.* gamma1:  skewness (Karl Fisher)
NB.* gamma2: kurtosis excess
NB.* skewSmall: skew for small sample.
NB.* stderr: standard error
NB.* teststat: test statistic: %/(skewSmall,stderr) y
NB.* mode: mode (largest category) of distribution.
NB.* pearson1: skew1 according to K. Pearson
NB.* pearson2: skew2 according to K. Pearson
NB.* quartile: breakpoint (max value) at which vector y ends quartile x
NB.* yule: Yule skewness measure
NB.* gamma: Gamma function of y
NB.* beta: Beta function of x and y
NB.* poissDist: Poisson distribution of states x with average number y
NB.* d29: xth moment of y
NB.* quantilify: make partition to break ordered vec y into x quantiles.
NB.* ntilebps: return breakpoint values of x-tiles of y; e.g. 4 ntile y -> quartiles;
NB.* bpntile: break vector into pieces based on (internal) breakpoints x
NB.* ntilebps: return breakpoint values of x-tiles of y; e.g. 4 ntilebps y
NB.* internalBPs: calculate internal breakpoints from quantile group.
NB.* kurtQuantile: kurtosis by quantiles, Chou, p.73.
NB.* kurt: kurtosis according to Excel documentation.
NB.* skew: skewness according to Excel documentation.
NB.* corrCoeff: coefficients of linear correlation between 2 columns of y
NB.* dFourierTransform: discrete Fourier transform due to Curtis Jones.
NB.* ftbasis: Basis function for Fourier transform
NB.* fourierTform: Fourier transform
NB.* invFourierTform: Inverse Fourier transform
