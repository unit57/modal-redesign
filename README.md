### Modal ReDesign:
<strong>Requires</strong><br>
* [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/components/) 
* [JQuery 3.2.1](https://developers.google.com/speed/libraries/#jquery)

Removed existing Bootstrap header and footer.<br>
New header designed for image - close button overlays image.<br>
Stylesheet marked up in style tags in index.html.<br>

<strong> Suggested Instructions </strong><br>
1. Make sure your project includes Bootstrap 3.3.7 and JQuery 3.2.1.
2. Clone repo.
3. Copy `<button>` in jumbotron and everything in between "Modal Start" and "Modal End" in your HTML 
4. Copy everything in between "Style Sheet Start" and "Style Sheet End" to your CSS file.

<strong> Reassign Trigger </strong> <br> 
To change modal trigger add the follwing to a new HTML element

`````
		  	data-toggle="modal" 
		  	data-target="#myModal"
`````
<br> and delete <br>
 
`````
		<button 
		  	type="button" 
		  	class="btn btn-info btn-lg" 
		  	data-toggle="modal" 
		  	data-target="#myModal">Open Modal</button>
		</div>
`````




View live [here](https://unit57.github.io/modal-redesign/).