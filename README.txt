This project is a Web application for Covid-19 ditection using CNN models (VGG16, ResNet50 and Xception)



We created 3 Notebook files for three models and loaded their weights at "cov_cnn_web\predictor\model_weights\ResNet50" folder in .hdf5 files.

View.py file conntains all the python code for fatching query of index.html giving the respose.

We used index.html file for webpage and style.css for style.



How to run the code :-

We used django web framework for web integration.You need to serup django environment in your system or location where your project is located.

Please check the requirements.txt file for the pre-requiests for running the project.

Then go to cmd ... go to the located path of your project and run manage.py file.

Ex. path> pyhton manage.py runserver (Manage.py file locatated at "Covid_CNN_WebApp\cov_cnn_web")

This will host your website on localhost and now you can use the website.

