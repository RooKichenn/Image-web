# Image-web
部署在web端的ImageNet图像识别

# Install
conda create -n web python=3.7
activate web
conda install pytorch==1.6.0 torchvision==0.7.0 cudatoolkit=10.1 -c pytorch
pip install streamlit

# Run
streamlit run app.py
