
AI Development                                                                                        
Hypervisual AI is currently developing a project that incorporates YOLOv13-N, with plans to integrate ViT-B-16 in future iterations.
                                                                                                    
Install Dependencies                                                              
git clone https://github.com/HypervisualAI-source/AI-Development.git                      
cd AI-Development
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt

Usage Guide
1. Training Model
    cd ./src/YOLOv13-N/
	python3 train.py      
	
2. Inferencing Model
    cd ./src/YOLOv13-N/                      
	python3 inference.py

3. Demonstrating YOLOv13-N 
    cd ./demos/YOLOv13-N/
	python3 demo.py 

3.1 Demonstrating YOLOv13-N in shell script file
    cd ./demos/YOLOv13-N/
    chmod +x demo.sh 
	./demo.sh

4. Demonstrating ViT-B-16
    cd ./demos/ViT-B-16/
	python3 demo.py                  
                                       
4.1 Demonstrating ViT-B-16 in shell script file
    cd ./demos/ViT-B-16/
    chmod +x demo.sh 
	./demo.sh
	
Dataset and Video
![Demo Video](check_0/object-track.gif)








