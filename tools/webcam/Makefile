<<<<<<< HEAD
CXXFLAGS=-Wall -Wextra --std=c++11 -I$(HOME)/Projects/openpilot -I$(HOME)/Projects/openpilot/cereal/messaging -L$(HOME)/Projects/openpilot/cereal -lmessaging_shared `pkg-config --libs --cflags kj capnp opencv`
=======
CXXFLAGS=-Wall -Wextra --std=c++11 -I$(HOME)/openpilot -I$(HOME)/openpilot/cereal/messaging -L$(HOME)/openpilot/cereal -lmessaging_shared `pkg-config --libs --cflags kj capnp opencv`
>>>>>>> 3916a466dadc063ff9be1a9b324a85f7dfdc7e96
CXX=g++

SOURCES=webcam.cc

all:
	$(CXX) -o webcamerad $(SOURCES) $(CXXFLAGS)
