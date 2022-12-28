MaxText
======

An LLM codebase that is:
* high-performance
* infinitely scalable
* open-source
* simple and easily forkable
* well-tested
for Cloud TPU customers

Install
========
manual setup:

```
bash setup.sh
```

Run
====
To run a training job:
```
python3 MaxText/train.py configs/base.yml run_name=$USER_$RANDOM
```

To lint:
```
pylint MaxText/
```


Status/TODO
======
[Backlog](http://go/maxtext-backlog)
