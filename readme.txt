
Epoch: 99 cost time: 4.252164363861084
Epoch: 99, Steps: 109 | Train Loss: 0.0254163 Val Loss: 0.4039532
        iters: 100, epoch: 100 | loss: 0.0255536
        speed: 0.1106s/iter; left time: 1.1057s
Epoch: 100 cost time: 4.85784912109375
Epoch: 100, Steps: 109 | Train Loss: 0.0251986 Val Loss: 0.4076888
>>>>>>>testing : ETTh1_1440_168_DDPM_ETTh1_ftM_sl1440_ll336_pl168_dt0_TWO<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
> test-shape (4320, 7) (4320, 7)
test 2713
Successfully loading trained model!
Elapsed time: 38.29 ms
Elapsed time: 40.90 ms
Elapsed time: 23.75 ms
Elapsed time: 25.37 ms
Elapsed time: 36.69 ms
id_worst 2
top5 [3 2 4 1 0]
mse|mae|rmse|mape|mspe|corr
0.41035238 0.4212738 0.6405875 9.32205 34339.9 25.59765

CUDA_VISIBLE_DEVICES=2 python main_ddpm.py --pretrain_epochs 10 --train_epochs 100 --is_training 1 --ddpm_layers_I 5 --cond_ddpm_channels_conv 32 --ddpm_layers_inp 5 --ablation_study_F_type Linear  --cond_ddpm_num_layers 30 --ddpm_layers_II 10 --learning_rate 0.0001 --label_len 336












