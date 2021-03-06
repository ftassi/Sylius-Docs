SyliusAddressingBundle
======================

Addressing system for Symfony2 applications.

With minimal configuration you can introduce addresses, countries, provinces and zones management into your project.
It's fully customizable, but the default setup should be optimal for most use cases.

It also contains zone matching mechanisms, which allow you to match customer addresses to appriopriate tax/shipping (or any other) zones.
There are several models inside the bundle, `Address`, `Country`, `Province`, `Zone` and `ZoneMember`.

There is also a **ZoneMatcher** service.
You'll get familiar with it in later parts of this documentation.

.. toctree::
   :numbered:

   installation
   address
   country_and_provinces
   zones
   forms
   Configuration reference <configuration>
