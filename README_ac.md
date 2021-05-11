run 

```
// get dependencies
pip install -r requirements.txt

// compile cython
// 	remove wrapped.c file (this is generated)
python setup.py build_ext --inplace

// run
python timing.py
```