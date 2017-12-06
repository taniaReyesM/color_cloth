# color_cloth
color_cloth gets the main colors and its proportions from a cloth image using the EM algorithm from OpenCV library, it assumes that the item is in the center of the image.

## Prerequisites
- **numpy:** `pip install numpy`
- **openCV:** `pip install opencv`

# e.g.

Image clustering with GMM...<br/>
```$ python color_cloth.py <path/to/image> ```

Some examples...<br/>
```$ python color_cloth.py images/29.jpg```<br/>
<a data-flickr-embed="true"  href="https://www.flickr.com/photos/153395371@N07/37176201684/in/dateposted-public/" title="Estampado"><img src="https://farm5.staticflickr.com/4502/37176201684_4a08874f7f.jpg" width="294" height="383" alt="Estampado"></a><br/>

```$ python color_cloth.py images/8.jpg```<br/>
<a data-flickr-embed="true"  href="https://www.flickr.com/photos/153395371@N07/24033973998/in/dateposted-public/" title="sombra"><img src="https://farm5.staticflickr.com/4495/24033973998_f00014bce3_n.jpg" width="320" height="274" alt="sombra"></a><br/>

```$ python color_cloth.py images/azul.jpg```<br/>
<a data-flickr-embed="true"  href="https://www.flickr.com/photos/153395371@N07/24033974588/in/dateposted-public/" title="prenda lisa"><img src="https://farm5.staticflickr.com/4462/24033974588_fe34be958a.jpg" width="347" height="399" alt="prenda lisa"></a>


Some images with complex background, the algorithm ignores the colors and shadows in the background and shows only the color of the cloth:

```$ python color_cloth.py images/22.jpg```<br/>
<a data-flickr-embed="true"  href="https://www.flickr.com/photos/153395371@N07/27085295559/in/dateposted-public/" title="Fondo complejo"><img src="https://farm5.staticflickr.com/4564/27085295559_56de965684.jpg" width="397" height="378" alt="Chamarra piel"></a>


```$ python color_cloth.py images/v.jpg```<br/>
<a data-flickr-embed="true"  href="https://www.flickr.com/photos/153395371@N07/38861561701/in/dateposted-public/" title="Blusa verde"><img src="https://farm5.staticflickr.com/4522/38861561701_c1ec28080e.jpg" width="300" height="347" alt="Blusa verde"></a>

