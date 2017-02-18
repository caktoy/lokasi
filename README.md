# Lokasi (en : Location)

*Lokasi* is simple library to *get()* and *set()* position of element with structure "Object Pattern" and compatible with AMD or Common JS module. *Lokasi* can use without dependency like jQuery etc. and its will be return _position_ of object / element with initialize on *class* like ```html <div class="target"></div> ``` and will be return parent of element too.

#### Note : Don't forget to set parent position with _relative_ and result of position will be affect for their parent

## How to use

*Lokasi* just have two method inner class *Lokasi* :

1. Method *_.get()_*

Use method *_.get()_* to get position and parent of object / element, this method will be return object like this :

``` javascript 
	
	Lokasi.get('.target-3');

	/* result
		{
			target: <div.target-3>,
			parent: <div.wrapper-1>, 
			left: 135,
			top: 18,
			right: 425,
			bottom: 124
		}
	*/
```

2. Method *_.set()_*

Use method *_.set()_* to set position of object / element, this method have 3 parameters to use _(target, offset left, offset right)_ :

``` javascript 
	
	Lokasi.set('.target-5', 20, 10);

	/* result
		{
			target: <div.target-5>,
			parent: <div.wrapper-2>, 
			left: 20,
			top: 10,
			right: 540,
			bottom: 30
		}
	*/
```

## License

Don't worry of license, just use it when you need. Contact me if you have problem for this library (muhibbudinsuretno1@gmail.com) or @muhibbudins (LinkedIn and Github). Thanks for watching