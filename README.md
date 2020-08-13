# E2PAT: Efficient discovery of emerging patterns from heterogeneous spatiotemporal data

E2PAT is a scalable method to comprehensively detect emerging patterns from heterogoeneous sources of spatiotemporal data generated by large sensor networks. We combine simplistic time differencing and spatial intersection principles to identify all emerging patterns distributed along geographies of interest. We show that the use of these principles guarantee a linear-time efficiency of E2PAT on the size of the input data. In addition, we propose an integrative score to measure the relevance of emerging patterns and show its role to support pattern retrieval, promote usability, and guarantee the actionability of the found patterns.

## Installation:

Python 3+

All dependencies defined in **requirements.txt**. You can install them by:

```
$ conda create --name <env> --file requirements.txt
$ conda activate <env>
```

## Usage:

After installing the required dependencies and activating your freshly created environment you should be able to run our app. 

You can see our interface for querying road traffic data by running and accessing http://127.0.0.1:8051/:

```
$ python emerging_patterns.py
```

You can test our solution by using the example data available at the `data/` folder. First you should run the interface and access http://127.0.0.1:8050/:

```
$ python emerging_patterns_from_csv.py
```

After accessing the interface choose to upload a file, then navigate to `data/` and choose `example-dataset.csv`.

---

 Please cite: contributions currently under review, contact Rui Henriques (rmch@tecnico.ulisboa.pt) or Francisco Neves (francisco.neves@tecnico.ulisboa.pt) to obtain the updated reference.

 Guidelines to access data are available upon request

