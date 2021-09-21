# MSVCL_MICCAI2021

## Installation

Please follow the instruction in [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) to install.

## Example Usage

An example of vendor-styes transfer from **GE** style to **HOLOGIC** style is provided:

python test.py --dataroot ./datasets/G/ --name G2H --model test  --input_nc 1 --output_nc 1 --preprocess none  --num_threads 4 --no_dropout --results_dir  ./datasets/ --epoch 100 --gpu_ids 0
