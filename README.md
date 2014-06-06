ProgArm-Hardware
================
Please set up these filters before commiting to this repository:
```
git config --global filter.clearsch.clean "sed 's/^Date.*$/Date \"\"/'"
git config --global filter.clearlib.clean "sed 's/^\(EESchema-LIBRARY Version [^ \\t]+\).*$/\1/'"
```
