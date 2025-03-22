# **Setting Up the Environment**

To ensure all dependencies are installed correctly, create a Conda environment using the provided YAML file:

```bash
conda env create -f final_environment.yml

```
Once the environment is created, activate it using:

```bash
conda activate mambair
```

# **Running the Superresolution Model**

After setting up the environment, use the following command to run the test script:
```sh
CUDA_VISIBLE_DEVICES=0 python test_demo.py --data_dir [path to your data dir] --save_dir [path to your save dir] --model_id 1
```
Explanation of Parameters:

--data_dir [path] : Path to the directory containing input images.

--save_dir [path] : Path where the output images will be saved.

--model_id 1 : Specifies which model to use for inference.