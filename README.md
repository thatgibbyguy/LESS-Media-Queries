# LESS-Media-Queries

Tired of writing your media queries out every time? Here's a LESS repo with most of the major media query breakpoints.


## Getting Started

You can use LESS Media Queries in one of two methods.

### Import Method

Clone or download the LESS file into your working directory. Then include LESS Media Queries at the top of your LESS Document.

```less

@import url('less/less-media-queries.less');

```

### Copy and Paste Method

Simply copy and paste the code contained in `less/less-media-queries.less` and paste it into your working LESS file. 

**IMPORTANT NOTE:** If you use this method please give the creators of this repo credit.

## Usage

Using LESS Media Queries is incredibly simple once you've imported or copied the code into your working LESS file. 

** Targeting iPhones **

LESS Media Queries currently gives you three methods to target iPhones.

* @iphoneFive
* @iphone
* @iphoneRetina

To target all iPhones you would simply include the following code into your working LESS file.

```less

/*Iphones */
	@media @iphone { /* STYLES GO HERE */ }

```

Additional usage examples are included in the `example-usage.less` file provided to you.

## Contributing

I (@thatgibbyguy) am very much open to contributions and/or suggestions for this repo. Any devices or suggestions you have please generate a pull request or tweet at me.

## Release History

* 2014-02-26   v0.0.1   Initial release.