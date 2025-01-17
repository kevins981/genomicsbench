Ecosystem notes:
To compile fmi, need to run two make files, in this particular order:
```
cd ../../tools/bwa-mem2
make # or, make all_occ_in_pmem
cd -
make # or, make all_occ_in_pmem
```
Note: the two makefiles should be invoked with the same target (e.g. all_occ_in_pmem).
(I should do this automatically, e.g. call bwa-mem2 makefile in fmi makefile)


`fmi` uses the same license as [BWA-MEM2](https://github.com/bwa-mem2/bwa-mem2).

If you use `fmi`, please cite:

```
@inproceedings{DBLP:conf/ipps/VasimuddinMLA19,
  author    = {Md. Vasimuddin and
               Sanchit Misra and
               Heng Li and
               Srinivas Aluru},
  title     = {Efficient Architecture-Aware Acceleration of {BWA-MEM} for Multicore
               Systems},
  booktitle = {2019 {IEEE} International Parallel and Distributed Processing Symposium,
               {IPDPS} 2019, Rio de Janeiro, Brazil, May 20-24, 2019},
  pages     = {314--324},
  publisher = {{IEEE}},
  year      = {2019},
  url       = {https://doi.org/10.1109/IPDPS.2019.00041},
  doi       = {10.1109/IPDPS.2019.00041},
  timestamp = {Wed, 16 Oct 2019 14:14:51 +0200},
  biburl    = {https://dblp.org/rec/conf/ipps/VasimuddinMLA19.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```


