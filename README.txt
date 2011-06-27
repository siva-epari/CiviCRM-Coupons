// $Id$

CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Installation


INTRODUCTION
------------

Civi Event Discounts module enables the discount features on event registration
forms based on:

1. Discount percentage
2. Discount amount

INSTALLATION
------------

1. Copy the civicrm_coupon directory to your sites/all/modules directory.

2. Enable the module at Administer >> Site building >> Modules.

3. Manage coupons here admin/settings/civicrm_coupon.

USAGE
-----

1. Create a coupon at admin/settings/coupon/add.
2. Create a paid CiviCRM event and enable online registration on it.
3. Goto online registration page for the event and you will find a "coupon" text box on the form.
4. Enter the coupon code and continue registration.
5. The selected discount format during coupon creation will be applied to all amounts on that form.
6. To view the usage report of coupons goto admin/settings/coupon/reports.


That's it! This module will automatically attempt to apply discounts
to any civicrm event registration form
