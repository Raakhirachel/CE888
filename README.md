# CE888
Navigate to code lacation path "Please check word embedding file and neccessary package are downloaded" : %cd Path name

Installing neccessary library packages :
  
  !pip2 install -r requirements.txt
  
  !pip2 install torch
  
  !pip2 install future
 
 Training phase - models of each features are saved on saved model folder : !python2.7 train.py --dataset data/
 
 Testing phase , sql queries for dev json are predicted on predicted_sql.txt file : !python2.7 test.py --output predicted_sql.txt
 
 The link for glove given : https://drive.google.com/file/d/1kBHlgGMypegAEstDTTrvOSC-G-JtbTE9/view?usp=sharing
 and also download the contents from this file as well: https://drive.google.com/file/d/1__4AU6rm6JYI1cZzghhh2XCNZIHnYoSN/view?usp=sharing                       
