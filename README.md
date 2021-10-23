## Nvdia Jetson Object Tracking
### Installation

#### Step 1 : Download the JetPack

You can find the JetPack from <a href='https://developer.nvidia.com/jetson-nano-sd-card-image'>here</a>.

#### Step 2 : Follow the Instruction for the installation
In order to run this application, of course you need to setup the Jetson before hand. You may follow the steps from this <a href='https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#intro'> website</a>.

The only thing is in the "Write Image to the microSD Card" step , you can skip the download "Jetson Nano Developer Kit SD Card Image" step as you have downloaded the JetPack.

#### Step 3 : Set up Camera
After you setup the jetson and it run perfectly, you can test the camera by following the guide <a href='https://developer.nvidia.com/embedded/learn/tutorials/first-picture-csi-usb-camera'>here</a>.


### Usage
After everything is done perfectly, you can try to run the application. I suggest that you run it from the terminal first because it can show the error if the application does not work on your side.

#### Step 1 : Open terminal


#### Step 2 : Direct to the project folder by running the command (based on where you place it)
```
cd Jetson_Tracker
```

#### Step3- Run the application by using the command
```
./UI
```

By right, the application should run after all this. FYI , the application is set to be fullscreen. To exit the full screen , you can press <F11> and you can press ESC key to exit the application.