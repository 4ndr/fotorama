Change navigation style from iPhone-style dots to&nbsp;thumbnails by&nbsp;adding `data-nav="thumbs"`:

	<div class="fotorama"
	     data-nav="thumbs">
	  <img src="1.jpg">
	  <img src="2.jpg">
	  <img src="3.jpg">
	</div>

For better performance with thumbnails, have smaller images ready and include them in&nbsp;<abbr>HTML</abbr>. Like&nbsp;so:

	<div class="fotorama"
	     data-nav="thumbs">
	  <a href="1.jpg"><img src="1_thumb.jpg"></a>
	  <a href="2.jpg"><img src="2_thumb.jpg"></a>
	  <a href="3.jpg"><img src="3_thumb.jpg"></a>
	</div>

_Thumbnails example (<a href="/examples/thumbnails.html#" target="_blank">new window</a>):_

<div class="fotorama-wrap"><div class="fotorama"
     data-width="500"
     data-ratio="3/2"
     data-max-width="100%"
     data-nav="thumbs">
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/1-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/1-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/2-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/2-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/4-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/4-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/5-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/5-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/6-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/6-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/7-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/7-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/8-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/8-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/9-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/9-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/10-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/10-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/11-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/11-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/12-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/12-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/13-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/13-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/14-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/14-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/15-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/15-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/16-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/16-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/20-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/20-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/21-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/21-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/22-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/22-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/23-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/23-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/24-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/24-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/17-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/17-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/18-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/18-thumb.jpg"></a>
	<a href="http://fotorama.s3.amazonaws.com/i/okonechnikov/19-lo.jpg"><img src="http://fotorama.s3.amazonaws.com/i/okonechnikov/19-thumb.jpg"></a>
</div></div>

By&nbsp;default, thumbnail is&nbsp;a&nbsp;64&times;64&nbsp;square. Adjust this with `data-thumb-width` and `data-thumb-height`.

Fotorama will automatically generate the missing thumbnails.

<!--To move navigation line on top, use `data-nav-position="top"`. Hide navigation with `data-nav="false"`.-->