# github.io
Child IAT
define(['pipAPI', 'https://futuredrboykin.github.io/github.io/'], function(APIConstructor, iatExtension){
    var API = new APIConstructor();

	return iatExtension({
		category1 : {
			name : 'Black students', //Will appear in the data.
			title : {
				media : {word : 'Black students'}, //Name of the category presented in the task.
				css : {color:'#31940F','font-size':'2em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		    {image : 'BM_09.jpg'}, 
    			{image : 'BM_10.jpg'}, 
    			{image : 'BM_11.jpg'}, 
    			{image : 'BM_12.jpg'}, 
			], 
			//Stimulus css (style)
			stimulusCss : {color:'#31940F','font-size':'1.8em'}
		},	
		category2 :	{
			name : 'White students', //Will appear in the data.
			title : {
				media : {word : 'White students'}, //Name of the category presented in the task.
				css : {color:'#31940F','font-size':'2em'}, //Style of the category title.
				height : 4 //Used to position the "Or" in the combined block.
			}, 
			stimulusMedia : [ //Stimuli content as PIP's media objects
    		    {image : 'WM_01.jpg'}, 
    			{image : 'WM_02.jpg'}, 
    			{image : 'WM_03.jpg'}, 
    			{image : 'WM_04.jpg'}, 
			], 
			//Stimulus css
			stimulusCss : {color:'#31940F','font-size':'1.8em'}
		},	

		base_url : {//Where are your images at?
			image : 'https://futuredrboykin.github.io/github.io/'
		} 
	});
});
