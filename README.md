LoremIpsumObjC
==============

LoremIpsum Generator for Objective-C. Just pass it the number of words you want, or if you want a special punctuation mark at the end of your NSString.

## Using LoremIpsum Generator ##

This is very, very straightforward. Drag both of these files (LoremIpsum.h, LoremIpsum.m) into your project, and make sure you click Add To Target. Import LoremIpsum.h in the class you are going to be generating your dummy text in. Then call this code whenever you need some dummy text:

```shell
NSString *yourString = [LoremIpsum generateLoremIpsumWithWords:295 punctuation:@"!"];
```

This takes an int for number of words, and a string for your punctuation. This means that, if you wanted, you could have your lorem ipsum string say anything at the very end. Like "Lorem ipsum, you idiot!" if you passed in 2 for number of words and @", you idiot!" for the punctuation.

## License ##

This is totally free of charge, and licensed under the standard MIT license. Happy coding.
