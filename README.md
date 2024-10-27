## G1020 Deep Learning Project

G1020 : 원본 이미지 데이터

Glaucoma_images : G1020/Images_Square에 있는 이미지 중 녹내장 이미지

Glaucoma_images_cropped : G1020/Images_Cropped에 있는 이미지 중 녹내장 이미지

Normal_images : G1020/Images_Square에 있는 이미지 중 정상 이미지

Normal_images_cropped : G1020/Images_Square에 있는 이미지 중 정상 이미지

위 이미지 파일 폴더는 크기 문제로 업로드 하지 못했음.

G1020 이미지를 아래 수행코드와 같은 폴더에 넣으면 코드에서 Deep_Square과 Deep_Cropped에서 
각각 (Glaucoma_images, Normal_images)와 (Glaucoma_images_cropped, Normal_images_cropped) 폴더를 만들고 
필요한 이미지를 복사함. 

simple_conv_3_128_128.ipynb : 128x128 칼라 이미지(r,g,b)로 축소한 simple convoultion 수행

simple_conv_1_128_128.ipynb : 128x128 흑백 이미지(grayscale)로 축소한 simple convolution 수행

simple_conv_1_64_64.ipynb : 64x64 흑백 이미지로 축소한 simple convolution 수행

simple_conv_1_64_64_batch.ipynb : 64x64 흑백 이미지로 축소하고, batch 크기 및 evaluate_sample_num_per_epoch를 조정한 simple convolution

Deep_Square.ipynb : 64x64로 축소한 흑백 이미지로 deep convoultion 수행

Deep_Cropped.ipynb : Cropped 이미지를 64x64의 흑백 이미지로 수정하여 deep convoltion 수행

 
