# CIFAR-Image-Classification
## CIFAR 10 Dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

Here are the classes in the dataset, as well as 10 random images from each:
airplane										
automobile										
bird										
cat										
deer										
dog										
frog										
horse										
ship										
truck										

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

## CIFAR 100 Dataset
This dataset is just like the CIFAR-10, except it has 100 classes containing 600 images each. There are 500 training images and 100 testing images per class. The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a "fine" label (the class to which it belongs) and a "coarse" label (the superclass to which it belongs).
Here is the list of classes in the CIFAR-100:

Superclass	Classes
aquatic - mammals	beaver, dolphin, otter, seal, whale <br>
fish - aquarium fish, flatfish, ray, shark, trout <br>
flowers	- orchids, poppies, roses, sunflowers, tulips <br>
food containers	- bottles, bowls, cans, cups, plates <br>
fruit and vegetables	- apples, mushrooms, oranges, pears, sweet peppers <br>
household electrical devices - clock, computer keyboard, lamp, telephone, television <br>
household furniture	- bed, chair, couch, table, wardrobe <br>
insects	- bee, beetle, butterfly, caterpillar, cockroach <br>
large carnivores	- bear, leopard, lion, tiger, wolf <br>
large man-made outdoor things	- bridge, castle, house, road, skyscraper <br>
large natural outdoor scenes	- cloud, forest, mountain, plain, sea <br>
large omnivores and herbivores	- camel, cattle, chimpanzee, elephant, kangaroo <br>
medium-sized mammals	- fox, porcupine, possum, raccoon, skunk <br>
non-insect invertebrates	- crab, lobster, snail, spider, worm <br>
people	- baby, boy, girl, man, woman <br>
reptiles	- crocodile, dinosaur, lizard, snake, turtle <br>
small mammals	- hamster, mouse, rabbit, shrew, squirrel <br>
trees	- maple, oak, palm, pine, willow <br>
vehicles 1	- bicycle, bus, motorcycle, pickup truck, train <br>
vehicles 2	- lawn-mower, rocket, streetcar, tank, tractor <br>

Yes, I know mushrooms aren't really fruit or vegetables and bears aren't really carnivores. 
