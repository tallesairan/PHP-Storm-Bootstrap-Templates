# Accordions

## `bs:accordion`

Just create the accordion container

	<div class="panel-group" id="accordion">
    	...
	</div>

## `bs:accordion:item`

Create an accordion item panel

	<div class="panel panel-default">
    	<div class="panel-heading">
      		<h4 class="panel-title">
        		<a data-toggle="collapse" data-parent="#accordion" href="#two">...</a>
      		</h4>
    	</div>
    	<div id="two" class="panel-collapse collapse">
      		<div class="panel-body">
        		...
      		</div>
    	</div>
  	</div>
	
## `bs:accordion:item:active`

Create an accordion active item

	<div class="panel panel-default">
    	<div class="panel-heading">
      		<h4 class="panel-title">
        		<a data-toggle="collapse" data-parent="#accordion" href="#one">...</a>
      		</h4>
    	</div>
    	<div id="one" class="panel-collapse collapse in">
      		<div class="panel-body">
        		...
      		</div>
    	</div>
	</div>