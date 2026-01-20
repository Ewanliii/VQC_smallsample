Each subfolder contains experimental content required for different dimensions. 
Taking D16 as an example (D8 and D32 follow the same principle), the contents include:

`y_labels.npy`: Labels corresponding to each row of Zdae_encoder.pt: Weights for the DAE encoder

`imputer.joblib`: Rules for imputing missing values

`scaler.joblib`: Rules for standardization

`Xy_small_N100_seed42` contains samples from the N=100 experiment

`Xy_small_N200_seed42` contains samples from the N=200 experiment

`Z_latent_D8.npy` contains nearly 600,000 data samples and their corresponding dimensions. Due to file size limitations, we will not upload it. It can be trained following the instructions in `DAE_trainer`.
