# Mixed Vinyl
Before this, I don't remember what was in older videos
## Video #5 | Symfony Flex: Aliases, Packs & Recipes

So we are installing templates and symfony knows when we give the composer require template. The reason behind because we have symfony/flex, this lib extends composers functionality.
Adding 3 superpowers:

1. Flex Aliases: composer require templates is an example where we give allies and install symfony/twig-pack package
2. Unpacking packs: a fake package that helps us to install other packages. It is bundled with dependencies of what you exactly need for a particular package.
3. Recipes: if a package has recipes, it will not just download the package to a vendor, flex also will execute recipes.

So we do flex and symfony will automatically add all things needed, like config and other stuff.

## Video #6 | Flex Recipes

It shows what exactly mean when you say recipes, composer require recipes to see all stuff that is installed. There is a command to see what information is about some recipe. Like composer recipes symfony/twig-bundle. There is a file called bundles.php, this file contains what plugins we use. Basically, bundles are plugins, this is adding symfony features.
Recipes give us the necessary files but on our own, if we want to change them or not.

## Video #7 | Twig

Learning about twig, this is a template engine, an example is homepage.html.twig 
1. Comments {# comment #}
2. Print {{ $nameOfVariable }}
3. Condition, Loops {% for $variable in $variables %} 
In the controller we extend AbstractionController which has methods, we use the render method which is a response, it expects two parameters, the first one is the name and location of templates, other is set of data we want to display.

## Video #8 | Twig inheritance

It is a way to put some content in place, we do inheritance. So we have a base twig file, in which we define a variable and template that extends the base template we put a keyword which we pass a variable name from our layout. We can put the value on parents as well.

## Video #9 | Profiler: Yours Debugging Best Friend

Debug bar is fantastic. Installing symfony/debug-pack we get a lot, of a great way of using it. So there are a lot of things to say like dump id does not stop executing the script it is actually rendering the template, and boom done.
You have a target section in symfony debug bar, and you can see what variable contains. Great, for sure my future best friend.

## Video #10 | Assets, CSS, Images, etc

