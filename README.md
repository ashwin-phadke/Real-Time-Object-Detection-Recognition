# Real-Time-Object-Detection-Recognition

Code for realtime object detection and recognition . The model is trained on caffe and uses OpenCV. The code iand it's testing was done on a CPU .

## Getting Started

- Download MobileNetSSD_deploy.caffemodel and MobileNetSSD_deploy.prototxt.txt for real time object detection.
- Host all the files on the same directory
- It is always a good practice to create a virtual environment for every project , not compuslory but ensures that dependencies are not hampered elsewhere.


### Installing



```
pip install -r requirements.txt
```




## Deployment

- Tested on 
  - Intel i3 6006U CPU
  - OS : Linux Fedora 28
  - 4GB RAM
  
## Best Results based on number of objects detected 

'''
To Run : python objdet.py -p [PATH TO PROTOTXT FILE] -m [PATH TO CAFFEMODEL DEPLOY] -c [CONFIDENCE]
'''



## Contributing

If you have any :


- Pull Requests : make one, work is always appreciated.
- Issues        : they are what help us improve, do create if any.
- Idea          : feature requests etc.
- Suggestions   : The world of Open Source



## Authors

* **Ashwin Phadke** 



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Amazing Ad.
* Open Source Community.
* Last mile contributors.
