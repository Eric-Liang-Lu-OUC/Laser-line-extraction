# pix2pix-laser line extraction

This is the code of our paper "Three-Dimensional Reconstruction with a Laser Line Based on Image In-Painting and Multi-Spectral Photometric Stereo", which was published on Sensors. It is mainly based on the code of Isola etc. (Isola, P .; Zhu, J.; Zhou, T.; Efros, AA Image-to-Image Translation with Conditional Adversarial Networks. In Proceedings of the 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Honolulu, HI, USA, 21 –26 July 2017; pp. 5967–5976).

On the basis of Isola's code, we added three strategies to the generator to implement an adaptive attention mechanism. The original network, which processes all pixels in the image, is improved to adaptively find the laser line in the image. Through finding the position of the laser line, performing image inpainting for pixels covered by the laser line, and almost doing nothing to the pixels which are not covered by the laser line, the network can achieve the "erasing" of the laser line in the multispectral image with a laser line. That is also equivalent to finding the laser line in the image.

If you find this code is helpful for your research, please cite our paper in the following ways:

MDPI and ACS Style
Lu, L.; Zhu, H.; Dong, J.; Ju, Y.; Zhou, H. Three-Dimensional Reconstruction with a Laser Line Based on Image In-Painting and Multi-Spectral Photometric Stereo. Sensors 2021, 21, 2131. https://doi.org/10.3390/s21062131

AMA Style
Lu L, Zhu H, Dong J, Ju Y, Zhou H. Three-Dimensional Reconstruction with a Laser Line Based on Image In-Painting and Multi-Spectral Photometric Stereo. Sensors. 2021; 21(6):2131. https:/ /doi.org/10.3390/s21062131

Chicago/Turabian Style
Lu, Liang; Zhu, Hongbao; Dong, Junyu; Ju, Yakun; Zhou, Huiyu. 2021. "Three-Dimensional Reconstruction with a Laser Line Based on Image In-Painting and Multi-Spectral Photometric Stereo" Sensors 21, no. 6 : 2131. https://doi.org/10.3390/s21062131
