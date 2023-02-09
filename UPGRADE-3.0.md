# Dependencies
* PHP 8.0 is the now the minimum

# Api
* \Mautic\Api\Api::getLogger now returns void as the LoggerAwareInterface dictates

# Contacts
* \Mautic\Api\Contacts::getEvents has been removed. Use \Mautic\Api\Contacts::getActivityForContact instead.

# Leads
* \Mautic\Api\Leads has been removed. Use \Mautic\Api\Contacts instead.

# Lists
* The \Mautic\Api\Lists has been removed. Use \Mautic\Api\Segments instead.

