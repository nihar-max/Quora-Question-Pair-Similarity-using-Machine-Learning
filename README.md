# Quora-Question-Pair-Similarity

Identify the Question asked on Quora is Duplicate of Questions which are already asked...

Eg: 1 


     
     Q1: Does johnny depp beats his wife ?
     Q2: Is Johnny Depp a wife beater?
     Ans : Simillar
    
Eg 2:



     Q1: Who is the highest paid actor currently?
     Q2: Who is the highest paid actor in Hollywood currently?
    Ans: Not Simillar
    
 ## Our Task
 
 .We have to Determine the questions asked are Duplicates or not.

.If eg: Q1 and Q2 are Duplicates then we can transfer the Answers from Q1 to Q2 which are already given by people.

Source : https://www.kaggle.com/c/quora-question-pairs

### Workflow

![image](https://user-images.githubusercontent.com/61958476/115405718-22146000-a20c-11eb-9d16-638d972cc235.png)

#### Load Datasets
![image](https://user-images.githubusercontent.com/61958476/115405933-50923b00-a20c-11eb-8d88-965d74000497.png)

#### EDA
![image](https://user-images.githubusercontent.com/61958476/115405985-5ee05700-a20c-11eb-9344-99cf4830991e.png)

#### Text Preprocessing
![image](https://user-images.githubusercontent.com/61958476/115406075-76b7db00-a20c-11eb-94b7-061d46727a7f.png)

#### NLP model TF-IDF Weighted W2V
![image](https://user-images.githubusercontent.com/61958476/115406146-8800e780-a20c-11eb-84cd-4f4d5d1a0a91.png)
![image](https://user-images.githubusercontent.com/61958476/115406241-9c44e480-a20c-11eb-924e-2d7e93ad2b99.png)


### SGD Classifier
![image](https://user-images.githubusercontent.com/61958476/115406322-af57b480-a20c-11eb-8bc8-121a1efc9683.png)
![image](https://user-images.githubusercontent.com/61958476/115406346-b4b4ff00-a20c-11eb-89d5-a4d73614c425.png)


### Decision Tree
![image](https://user-images.githubusercontent.com/61958476/115406406-c26a8480-a20c-11eb-90a9-10c201461e0b.png)
![image](https://user-images.githubusercontent.com/61958476/115406427-c8f8fc00-a20c-11eb-9aaa-a217b410bb8c.png)


### Compare 2 models
![image](https://user-images.githubusercontent.com/61958476/115406473-d4e4be00-a20c-11eb-8c0e-367eebffb827.png)

