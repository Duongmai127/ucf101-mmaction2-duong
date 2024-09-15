# ucf101-mmaction2-duong

In this attempt, we fine-tune a pre-trained C3D model to the UCF101 action recognition dataset. Due to limited computing hardware, the model is trained and evaluated on train and validation splits each in only 1 epoch. Out of the 3 train splits indexed 1, 2, 3, and the 3 validation counterparts indexed likewise, the model is trained on train split #1 and evaluated on validation split #1.


Check out work_dirs/c3d_sports1m-pretrained_8xb30-16x1x1-45e_ucf101-rgb/c3d_sports1m-pretrained_8xb30-16x1x1-45e_ucf101-rgb.py to see relevant details in training a model (e.g. model architecture, weight initialization, train/val dataset, data pipeline, data loader, optimizer schemes, default hooks)


Check out data/ucf101 to see the off-the-shelf train/validation splits that come with MMAction2
