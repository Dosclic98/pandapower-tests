# pandapower-tests
Repository for the tests performed in pandapower regarding possible attack vectors and scenarios

## Installing the correct pandapower version
Install my fork of pandapower otherwise the ```pf_res_plotly``` function [will not display the line loading colorbar](https://github.com/e2nIEE/pandapower/pull/2763).
It should have been fixed in pandapower v. 3.2.1 but it is not for some unknown reason.

```bash
# Clone the pandapower fork somewhere
git clone -b develop git@github.com:Dosclic98/pandapower.git

# Move into the folder
cd pandapower

# Install it in the currently active virtual environment
pip install .
```