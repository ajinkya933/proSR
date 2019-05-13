# ProSR

**RUN** 

1.  Export PYTHONPATH=/Users/ajinkyabobade/Downloads/proSR-master/lib:$PYTHONPATH
2.  Download data from https://drive.google.com/drive/folders/1ftVyi6p3uKJYbsatnAbtrjY9Z3aFy23s?usp=sharing. place the data in proSR-master folder

Run Demo from existing checkpoints using: 
'''python3 test.py --checkpoint data/checkpoints/proSRGAN_x8.pth --target data/datasets/DIV2K/DIV2K_valid_HR2 --scale 2 --output-dir output
