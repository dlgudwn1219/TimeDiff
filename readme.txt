$python main_ddpm.py --pretrain_epochs 10 --train_epochs 100 --is_training 1 --ddpm_layers_I 5 --cond_ddpm_channels_conv 32 --ddpm_layers_inp 5 --ablation_study_F_type Linear  --cond_ddpm_num_layers 30 --ddpm_layers_II 10 --learning_rate 0.0001 --label_len 336

(after train, is_training can be set to 0)

result saved in ./result_logs/result.txt
MSE loss for ETTh1 data univariate, multivariate reproduced









