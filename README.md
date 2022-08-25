# Cast-GAN: Learning to Remove Colour Cast in Underwater Images
<p align="center">
Chau Yi Li*, Andrea Cavallaro</br>
Queen Mary University of London, London, United Kingdom</br>
*chauyi.li@qmul.ac.uk</br>
</p>
<p align="center">
 <img src="https://user-images.githubusercontent.com/26412181/186699466-2e675662-2000-40d6-8719-30662eedea8a.png" data-canonical-src="[https://user-images.githubusercontent.com/26412181/186698205-7b3a9aae-a997-47d1-af95-517649650560.png](https://user-images.githubusercontent.com/26412181/186699466-2e675662-2000-40d6-8719-30662eedea8a.png)" width="48%"/>  
  <img src="https://user-images.githubusercontent.com/26412181/186698205-7b3a9aae-a997-47d1-af95-517649650560.png" data-canonical-src="https://user-images.githubusercontent.com/26412181/186698205-7b3a9aae-a997-47d1-af95-517649650560.png" width="48%"/>
</p>
<p align="center"> Underwater image under low light (left)  enhanced by Cast-GAN (right). </p>

## Abstract
Underwater images are degraded by blur and colour cast caused by the attenuation of the illuminant in the water medium. To remove the colour cast with neural networks, images of the scene taken under white illumination are needed as reference for training, but are generally unavailable. As an alternative, one can use surrogate reference images taken close to the water surface or degraded images synthesised from reference datasets. However, the former still suffer from colour cast and the latter generally have limited colour diversity. To address these problems, we exploit open data and typical colour distributions of objects to create a synthetic image dataset that reflects degradations naturally occurring in underwater photography. We use this dataset to train Cast-GAN, a Generative Adversarial Network whose loss function includes terms that eliminate artifacts that are typical in underwater images enhanced with neural networks. We compare the enhancement results of Cast-GAN with four state-of-the-art approaches and validate with a subjective evaluation.

## Testing

- Testing Cast-GAN 
```
python test.py
```

# Citation
If you use the sample code or part of it in your research, please cite the following:

```
@ARTICLE{Cast-GAN_Li_2020,
       author = {{Li}, C.Y. and {Cavallaro}, A.},
        title = "{Cast-GAN: Learning to Remove Colour Cast in Underwater Images}",
      journal = {International Conference on Image Processing},
         year = 2020,
        month = Sep,
}
```

