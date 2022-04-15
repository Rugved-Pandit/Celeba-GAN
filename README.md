# Celeba-GAN

GAN made using the Celeba dataset and CNN models for generator and discriminator.

## Generative Adversarial Networks (GAN)
GAN are used to generate synthetic data based on the given dataset. It is a type of architecture where a pair of generator and discriminator are trained together until the generator becomes capable of producing data that can pass as the original data.

## Results
It takes a very large number of epochs to train a gan due to it's complexity. 

Here are some results when model was trained on 40,000 images and 32 epochs

![gan_generated_image 32](https://user-images.githubusercontent.com/62091349/163630991-6084809c-2688-439d-b11d-2fb4b925e8cb.png)

and 37 epochs

![gan_generated_image 37](https://user-images.githubusercontent.com/62091349/163631427-78f20489-e5eb-4639-864b-481f30f2d2b9.png)

it has started to learn the features of a human face. Training for another 100 epochs and rest of the unused dataset can give significantly better results.
