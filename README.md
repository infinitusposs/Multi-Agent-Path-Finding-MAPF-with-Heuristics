## How to run the code:
	```python run_experiments.py --instance custominstances/[file name for the instance] --solver CBS --heuristic [heuristic]```

Values for [heuristic]: None, CG, DG, WDG

Example:
	```python run_experiments.py --instance custominstances/1.txt --solver CBS --heuristic DG```

	This means running instance 1 with DG heuristic.

Instances indicated in the report are in the directory "custominstances". The file name is the same as the instance name. 
