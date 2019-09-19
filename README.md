# U2GAN: Unsupervised Universal Self-Attention Network for Graph Classification

python train_u2GAN_noPOS.py --dataset COLLAB --batch_size 512 --ff_hidden_size 1024 --num_neighbors 8 --num_sampled 512 --num_epochs 50 --num_hidden_layers 4 --learning_rate 0.00005 --model_name COLLAB_bs512_dro05_1024_8_idx0_4_3

python train_u2GAN_noPOS.py --dataset IMDBBINARY --batch_size 128 --ff_hidden_size 1024 --num_neighbors 8 --num_sampled 512 --num_epochs 50 --num_hidden_layers 1 --learning_rate 0.0005 --model_name IMDBBINARY_bs128_dro05_1024_8_idx0_1_1

python train_u2GAN_noPOS.py --dataset IMDBMULTI --batch_size 128 --ff_hidden_size 1024 --num_neighbors 16 --num_sampled 512 --num_epochs 50 --num_hidden_layers 3 --learning_rate 0.0005 --model_name IMDBMULTI_bs128_dro05_1024_16_idx0_3_1

python train_u2GAN_noPOS.py --dataset DD --batch_size 512 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 4 --num_sampled 512 --num_epochs 50 --num_hidden_layers 3 --learning_rate 0.00005 --model_name DD_bs512_dro05_1024_4_idx0_3_3

python train_u2GAN_noPOS.py --dataset ENZYMES --batch_size 128 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 4 --num_sampled 512 --num_epochs 50 --num_hidden_layers 2 --learning_rate 0.0005 --model_name ENZYMES_bs128_dro05_1024_4_idx0_2_1

python train_u2GAN_noPOS.py --dataset NCI1 --batch_size 128 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 8 --num_sampled 512 --num_epochs 50 --num_hidden_layers 4 --learning_rate 0.00005 --model_name NCI1_bs128_dro05_1024_8_idx0_4_3

python train_u2GAN_noPOS.py --dataset NCI109 --batch_size 128 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 8 --num_sampled 512 --num_epochs 50 --num_hidden_layers 5 --learning_rate 0.00005 --model_name NCI109_bs128_dro05_1024_8_idx0_5_3

python train_u2GAN_noPOS.py --dataset PTC --batch_size 128 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 8 --num_sampled 512 --num_epochs 50 --num_hidden_layers 6 --learning_rate 0.0005 --model_name PTC_bs128_dro05_1024_8_idx0_6_1

python train_u2GAN.py --dataset MUTAG --batch_size 128 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 4 --num_sampled 512 --num_epochs 50 --num_hidden_layers 4 --learning_rate 0.0005 --model_name MUTAG_bs128_dro05_1024_4_idx0_4_1

python train_u2GAN.py --dataset PROTEINS --batch_size 128 --degree_as_tag --ff_hidden_size 1024 --num_neighbors 16 --num_sampled 512 --num_epochs 50 --num_hidden_layers 5 --learning_rate 0.0005 --model_name PROTEINS_bs128_dro05_1024_16_idx0_5_1
