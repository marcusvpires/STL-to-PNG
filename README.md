# STL-to-PNG

The script scans for any `.stl` files in the same directory it is run from. For each file found, it automatically generates three `.png` images with a semi-transparent black background, showing the 3D model from different angles:

  * Front view
  * Side view
  * Top view

```bash
pip install numpy-stl vtkplotlib
```


```bash
python your_script_name.py
```
