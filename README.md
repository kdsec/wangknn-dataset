# wangknn-dataset
Dataset of 'Effective Attacks and Provable Defenses for Website Fingerprinting', mirrored from `https://www.cse.ust.hk/~taow/wf/data/`

```
@inproceedings{Wang2014Effective,
  title={Effective attacks and provable defenses for website fingerprinting},
  author={Wang, Tao and Cai, Xiang and Nithyanand, Rishab and Johnson, Rob and Goldberg, Ian},
  booktitle={Usenix Conference on Security Symposium},
  pages={143-157},
  year={2014},
}
```


### Description

This data set consists of 100 monitored pages (90 traces each) and 9000 unmonitored pages (1 trace each).

### Directory Structure

```
./
|_ data.zip
	|_ <monitored_page_num>-<trace_num>
	|_ <unmonitored_page_number>
```

For example, `100-20` includes the 20th cell sequence of No.100 page.

### Quick Look

batch/1-1:

```
0.0     1
0.0     1
0.198159217834  1
0.380212068558  -1
0.380212068558  -1
0.53525519371   1
0.552129030228  -1
0.562554121017  -1
0.562554121017  -1
```

| Time | Direction  |
| --- | --- |


