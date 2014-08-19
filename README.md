Victoire CMS Slider Listing Widget Bundle
============

This bundle is a slider widget extending the widget Listing.
To use this widget, you must *obviously* install this widget in a Victoire project.

Then you just have to run the following composer command in your projet :

    php composer.phar require victoire/slider-bundle

Do not forget to add the bundle in your AppKernel !

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                ...
                new Victoire\Widget\SliderBundle\VictoireWidgetSliderBundle(),
            );

            return $bundles;
        }
    }

[![Licence Creative Commons](http://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

This product is provided under [Licence Creative Commns Attributions - No commercial use - No share 4.0 France](http://creativecommons.org/licenses/by-nc-nd/4.0/fr/) terms.
