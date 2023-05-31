# clip-encoder--t5-decoder-
Here I have implemented a transformer by using clip as encoder and t5 as decoder

STEP-1
Run parse_coco.py to generate a pickle file , but to simplify i have already generated the pickle file and uploaded 
in google drive you can download it from there and just paste it in your local folder clip-encoder--t5-decoder-\data\coco\"
https://drive.google.com/file/d/1Q_lW5rNvq-kSpby3u7iKTLZVMvC_CFpQ/view?usp=share_link
https://drive.google.com/file/d/11ierTbX5mUGM0oUFMDxO7iaQ73Uj7n6e/view?usp=share_link


STEP-2
In training.ipynb file go to the main function and make changes in the '--data','--out_dir' line by specifying the directory of pickle file you downloaded in step-1
and by specifying the target destination of trained pytorch weights
parser.add_argument('--data', default=r'C:\Users\KIIT\Documents\GitHub\CLIP_prefix_caption\data\coco\oscar_split_ViT-B_32_train.pkl') 
parser.add_argument('--out_dir', default=r'C:\Users\KIIT\Documents\GitHub\clip-encoder--t5-decoder-\pretrained_models')
due to no hardware access i have trained only till one epoch  you can download by the link below
https://drive.google.com/file/d/1wr9_7n0v-a15H64TyK92WnqR1mA4fY87/view?usp=share_link

STEP-#
Run the clip_prefix_captioning_inference.ipynb under the notebook sub directory

