## FasterViT: Fast Vision Transformers with Hierarchical Attention

![image](https://github.com/AarohiSingla/FasterViT/assets/60029146/35e7d081-0f4c-49af-bf03-73aaa70b2c7e)

#### Tutorial (What is FasterVit and How to use Pretrained Model): https://youtu.be/0Xc3qQeZlIU

#### Tutorial ( How to work with custom dataset) : https://youtu.be/m5iWjkewmtk


#### Ofiicial Github Repo: https://github.com/NVlabs/FasterViT

#### Paper: https://arxiv.org/pdf/2306.06189

#### Environment setup: 
          This code is tested on python 3.11
          
          python.exe -m pip install --upgrade pip
          
          pip install fastervit>=0.9.8
          
          # Get requirements.txt from here:   https://github.com/NVlabs/FasterViT/blob/main/requirements.txt
          
          pip install -r requirements.txt
          
          pip install matplotlib
          
          pip install opencv-python
          
          # Create a tmp folder where pretrained model will be downloaded.

A pretrained FasterViT model with default hyper-parameters can be created as in:

     from fastervit import create_model
     
     Define fastervit-0 model with 224 x 224 resolution
     
      model = create_model('faster_vit_0_224', 
                               pretrained=True,
                               model_path="/tmp/faster_vit_0.pth.tar")

A pretrained FasterViT model with default hyper-parameters can be created as in:

     from fastervit import create_model
     
      Define fastervit-0 model with 224 x 224 resolution
     
     model = create_model('faster_vit_0_224', 
                               pretrained=True,
                               model_path="/tmp/faster_vit_0.pth.tar")




##### model_path is used to set the directory to download the model.
