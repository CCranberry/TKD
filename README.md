To measure the dataset on embedded devices such as Jetson TX2: 
1.copy the program to your target device 
2.create a soft link from dataset_tx2 to dataset: ln -s dataset_tx2 dataset 
3.create a folder named 'measure_records' under dataset_tx2 to save the measure records
3.run measure_programs.py
