# Welcome to Pycon Canada!

In this tutorial, you will learn how to train your own image classification model using transfer learning. The Azure Machine Learning python SDK's [PyTorch estimator](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-train-pytorch) enables you to easily submit PyTorch training jobs for both single-node and distributed runs on Azure compute. The model is trained to classify dog breeds using a pretrained ResNet18 model that has been trained on the [Stanford Dog dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/). This dataset has been built using images and annotation from ImageNet for the task of fine-grained image categorization. For time, we will use a subset of this dataset which includes 10 dog breeds.

You can view the subset of the data used [here](https://github.com/heatherbshapiro/pycon-canada/tree/master/breeds-10). 

Please refer to the dog-breed-classifier.ipynb notebook for instructions.

The full list of dog breeds in the full dataset:
 			
            ['Chihuahua',
             'Japanese_spaniel',
             'Maltese_dog',
             'Pekinese',
             'Shih',
             'Blenheim_spaniel',
             'papillon',
             'toy_terrier',
             'Rhodesian_ridgeback',
             'Afghan_hound',
             'basset',
             'beagle',
             'bloodhound',
             'bluetick',
             'black',
             'Walker_hound',
             'English_foxhound',
             'redbone',
             'borzoi',
             'Irish_wolfhound',
             'Italian_greyhound',
             'whippet',
             'Ibizan_hound',
             'Norwegian_elkhound',
             'otterhound',
             'Saluki',
             'Scottish_deerhound',
             'Weimaraner',
             'Staffordshire_bullterrier',
             'American_Staffordshire_terrier',
             'Bedlington_terrier',
             'Border_terrier',
             'Kerry_blue_terrier',
             'Irish_terrier',
             'Norfolk_terrier',
             'Norwich_terrier',
             'Yorkshire_terrier',
             'wire',
             'Lakeland_terrier',
             'Sealyham_terrier',
             'Airedale',
             'cairn',
             'Australian_terrier',
             'Dandie_Dinmont',
             'Boston_bull',
             'miniature_schnauzer',
             'giant_schnauzer',
             'standard_schnauzer',
             'Scotch_terrier',
             'Tibetan_terrier',
             'silky_terrier',
             'soft',
             'West_Highland_white_terrier',
             'Lhasa',
             'flat',
             'curly',
             'golden_retriever',
             'Labrador_retriever',
             'Chesapeake_Bay_retriever',
             'German_short',
             'vizsla',
             'English_setter',
             'Irish_setter',
             'Gordon_setter',
             'Brittany_spaniel',
             'clumber',
             'English_springer',
             'Welsh_springer_spaniel',
             'cocker_spaniel',
             'Sussex_spaniel',
             'Irish_water_spaniel',
             'kuvasz',
             'schipperke',
             'groenendael',
             'malinois',
             'briard',
             'kelpie',
             'komondor',
             'Old_English_sheepdog',
             'Shetland_sheepdog',
             'collie',
             'Border_collie',
             'Bouvier_des_Flandres',
             'Rottweiler',
             'German_shepherd',
             'Doberman',
             'miniature_pinscher',
             'Greater_Swiss_Mountain_dog',
             'Bernese_mountain_dog',
             'Appenzeller',
             'EntleBucher',
             'boxer',
             'bull_mastiff',
             'Tibetan_mastiff',
             'French_bulldog',
             'Great_Dane',
             'Saint_Bernard',
             'Eskimo_dog',
             'malamute',
             'Siberian_husky',
             'affenpinscher',
             'basenji',
             'pug',
             'Leonberg',
             'Newfoundland',
             'Great_Pyrenees',
             'Samoyed',
             'Pomeranian',
             'chow',
             'keeshond',
             'Brabancon_griffon',
             'Pembroke',
             'Cardigan',
             'toy_poodle',
             'miniature_poodle',
             'standard_poodle',
             'Mexican_hairless',
             'dingo',
             'dhole',
             'African_hunting_dog']
