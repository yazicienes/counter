sudo apt install python3-opencv
sudo apt install python3-numpy
sudo install python3-pip
pip3 install face_recognition
sudo apt install cmake
sudo apt install git
git clone https://github.com/davisking/dlib.git
cd dlib
mkdir build
cd build
cmake ..
cmake --build
cd ..
sudo python3 setup.py install
