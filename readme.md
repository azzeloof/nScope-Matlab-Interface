# nScope Matlab Interface

This project is a Matlab app designed to interface with a nScope USB oscilloscope.
It requires the nScopeAPI, which can be found at https://github.com/nLabs-nScope/nScopeAPI.
To use this app, clone the API, and add ../matlab to your Matlab path. After that, the app
should run.

Note that editing the source requires Matlab 2016, because it was made in the App Designer
tool.

Current version (alpha-0.3) is (hopefully) almost suitable for use.
Lags when run at higher speeds (runs perfectly at 25 hz with one channel).
Version alpha-0.3 drastically improves lag problems.

Install "nScope Matlab Interface.mlappinstall" in matlab to use.

Please note that this project is not at all officially associated with nScope.

![Screenshot](/img/alpha-0_3 screenshot.png)
