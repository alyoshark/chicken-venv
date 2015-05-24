# chicken-venv
A tiny utility to mimic Python virtualenv steps in Chicken Scheme

## Usage

```
# Think of an awesome name for an imaginary coop and put it somewhere that fits :)
echo VENV=~/chicken/mycoop
chicken-venv $VENV
```

And _voilà_ the virtualenv is setup :)

```
. $VENV/bin/activate      # To activate a chicken virtualenv
. deactivate  			  # To deactivate :)
```
