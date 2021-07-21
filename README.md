# Social-Distancing

To combat COVID-19 outbreak by helping the Government implement  Social Distancing efficiently 
Would capture the video and detect people in real-time.(used SSD)
If people too close: a red bounding box is displayed around them implies the required distance is not being maintained
 




Run with the following command

python3 social_dist.py --video test_sample.mp4 --prototxt SSD_MobileNet_prototxt.txt --model SSD_MobileNet.caffemodel --labels class_labels.txt
