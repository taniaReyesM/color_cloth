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

