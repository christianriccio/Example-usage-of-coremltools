# Example usage of coremltools module 

This repo works as a basic example of usage of the python module named coremltools. 
This module allows you to convert your custom ML model written in python (using the well known frameworks such as: keras, tensorflow, pytorch, and so on..) to a .mlmodel file. This is intended for those who works in iOS appe development and wants to built their custom ML models to bring under the hood of their app. 

I provide a python jupyter notebook where i built my custom MLP to perform image classification on the famous mnist dataset and then, by using coremltools, I exported it as mlmodel file ready to be used within the Xcode project. (the file is also provided).

Note: don't mind about the warning of some cells, there are some fixes to do on my new M1 macbook pro and the python environment. Everything works the same !

Be aware of the fact that this wants only to be an example, so you are invited to have a look at the official documentation* of coremltools to look at all its capabilities !


official documentation: https://coremltools.readme.io/docs/what-are-coreml-tools
