ProgArm-Hardware
================
**NB! This project is in active development and things are changing all the time. Gerber files are currently outdated.**

Please set up these filters before commiting to this repository:
```
git config --global filter.cleansch.clean "sed 's/^Date.*$/Date \"\"/'"
git config --global filter.cleanlib.clean "sed 's/^\(EESchema-LIBRARY Version [^ \\t]*\).*$/\1/'"
git config --global filter.cleanpcb.clean "sed 's/\(host pcbnew \"\)[^\"]*/\1/'"
git config --global filter.cleanpro.clean "sed 's/^\(update=\).*$/\1/'"

```
