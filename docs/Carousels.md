# Carousels

## `bs:carousel`

	<div id="$id$" class="carousel slide" data-ride="carousel">
		<!-- Indicators -->
  		<ol class="carousel-indicators">
    		<li data-target="#$id$" data-slide-to="0" class="active"></li>
    		<li data-target="#$id$" data-slide-to="1"></li>
    		<li data-target="#$id$" data-slide-to="2"></li>
  		</ol>

  		<!-- Wrapper for slides -->
  		<div class="carousel-inner">
    		<div class="item active">
      			<img src="$img_src$" alt="$img_alt$">
      			<div class="carousel-caption">
        			$content$
      			</div>
    		</div>
    		$END$
  		</div>

  		<!-- Controls -->
  		<a class="left carousel-control" href="#$id$" data-slide="prev">
    		<span class="glyphicon glyphicon-chevron-left"></span>
  		</a>
  		<a class="right carousel-control" href="#$id$" data-slide="next">
    		<span class="glyphicon glyphicon-chevron-right"></span>
  		</a>
	</div>

## `bs:carousel:controls`

	<a class="left carousel-control" href="#$id$" data-slide="prev">
    	<span class="glyphicon glyphicon-chevron-left"></span>
  	</a>
  	<a class="right carousel-control" href="#$id$" data-slide="next">
    	<span class="glyphicon glyphicon-chevron-right"></span>
  	</a>
	
## `bs:carousel:indicator`

	<li data-target="#$id$" data-slide-to="2">$END$</li>
	
## `bs:carousel:slide`

	<div class="carousel-inner">
    	<div class="item active">
      		<img src="$img_src$" alt="$img_alt$">
      		<div class="carousel-caption">
        		$END$
      		</div>
    	</div>
  	</div>