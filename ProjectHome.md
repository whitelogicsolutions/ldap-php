ldap-php is an attempt to create a ldap client (and server interface) in pure php. It includes a ber/der de-/encoder (enough to de-/encode ldap messages) .

I have started to experiment with decoding x509 certificates and using it for doing OCSP and CRL.

It requires BigInteger.php (http://pear.php.net/package/Math_BigInteger).