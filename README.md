# Nuberu

Here we provide a dataset, split into 2 files, corresponding to a comprehensive set of uplink LTE experiments between one srseNB and one srsUE node using a wireless channel in band 3. This dataset has been used in https://doi.org/10.1145/3447993.3483266

"id": Unique Subframe identifier         
"tti": TTI number (There are duplicates because TTI number is recycled, hence "id" column)         
"cb_index": Code block index (Each transport block has a maximum of 2 code blocks in these experiments)
"it": Turbo decoder iteration 
"total_its": Total turbo decoder iterations for the corresponding codeblock    
"ext1_avg": Average value of the extrinsic values output by the convolutional decoder 1     
"ext2_avg": Average value of the extrinsic values output by the convolutional decoder 2       
"ext1_avg_abs": Average absolute value of the extrinsic values output by the convolutional decoder 1   
"ext2_avg_abs": Average absolute value of the extrinsic values output by the convolutional decoder 2 
"cb_size": Code block size      
"tbs": Transport block size         
"mcs": 3GPP Modulation and Conding Scheme index          
"snr": Signal-to-noise ratio          
"dec_time": Decoding time in one Intel Xeon x86 core @ 1.9GHz     
"avg_it_block": Average number of iterations per block 
"crc": CRC validation after finishing decoding (or reaching maximum number of 10 iterations). 1 (OK) or 0 (KO).         
"filename": filename


## Citing Work
If you use any code please cite the following:
```
@inproceedings{saavedra2021nuberu,
  title={Nuberu: Reliable RAN Virtualization in Shared Platforms},
  author={Garcia-Aviles, Gines and Garcia-Saavedra, Andres and Gramaglia, Marco and Costa-Perez, Xavier and Serrano, Pablo and Banchs, Albert},
  year = {2021},
  isbn = {9781450361699},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3447993.3483266},
  doi = {10.1145/3447993.3483266},
  booktitle = {The 25th Annual International Conference on Mobile Computing and Networking},
  location = {New Orleans, LA, USA},
  series = {MobiCom '21}
}
```

