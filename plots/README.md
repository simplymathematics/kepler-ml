To render the newest results.
```
cd ~/deckard
git fetch <upstream name>
git checkout fix-compile-script
cd examples/power/plots
dvc repro --downstream compile
```
