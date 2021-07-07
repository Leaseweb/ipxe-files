ipxe-files
----------

This is a collection of `ipxe` files that can be used with Leaseweb Custom
Install feature to boot OS images.

For more information on `pxe` booting with `ipxe`:

https://ipxe.org


usage
-----

To boot these OS'es here you need to create a DHCP reservations for your
Dedicated Server, documentation how you can do this via the API is here:

https://developer.leaseweb.com/api-docs/dedicatedservers_v2.html#operation/servers-leases-post


A more in-depth explanation of what is required and how to create a Custom
DHCP Reservation via the Leaseweb Customer Portal can be found on the Leaseweb
Knowledg Base here:

https://kb.leaseweb.com/products/dedicated-server/installing-servers-using-your-own-pxe-boot-environment


contribute
----------

If you want to add a new OS, or fix a bug, contributions are welcome.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Make sure that tests pass (`make test`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request
