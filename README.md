训练时，需要原图和相应标签集，分别放入stack 和 mask文件夹。首先使用data_nuclear.py将图像数据集（tiff格式）处理为npy文件，然后使用unet_nuclear.train.py进行训练。
测试时，对于原图（stack文件夹），使用predict_more_whole.py进行预测，然后使用final.m进行后处理，结果分别放在pythonout文件夹和final文件夹内。
