README.txt

Code in this directory are horizontal and are required for the working of the
majority of applications. eg. login, permissions, forms

A. It is preferred that libraries are made available to packagist
and are placed in the vendor directory (independant of codeigniter).

i.  Where third party packages are not available on packagist eg formsgeneration by lemos, they are placed here
ii. Where code has been written and is not yet of sufficient quality / compliant with the php package checklist

http://phppackagechecklist.com

iii. Glue code between framework agnostic code available from Packagist and Codeigniter
This glue code includes 'loaders' to load only the code required for a specific controller type.

iv. Continue with the lightweight CI principle of loading only what is necessary for a specific controller to function.

v. All the code in these libraries is open source.

The primary uses of codeigniter

i.   MVC separation
ii.  Url routing
iii. Internationalisation

B. All other mechanisms are to be delegated out to framework agnostic code for portability

C. Specific website functions (widgets) eg bookings, houseshare search, contract creation are to be created in third party directories.
This will enable a third party development company to
i.   Leverage off the framework to reduce development time
ii.  Enable third party functions to be interoperable without requiring APIs [use an array format instead]
iii. Each third party directory (widget) is self funding, profit making. The enable transactions to occur, which are chargable.
