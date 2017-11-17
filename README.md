# DynSilo
Perl script to keep your Name Silo domain record in sync with your IP address


This is a simple script to take advantage of the NameSilo.com API to turn your domain there into a dynamic IP, similar to services provided by dyndns, noip, and so on.

You will have to have your domain registered with NameSilo, and you'll have to generate an API Key here: https://www.namesilo.com/account_api.php.

You should be able to run this from the command line or as a CGI, there are just a few variables you need to assign in the top of the script. 
To run as a CGI, you'll use http://example.com/cgi-bin/dynsilo.pl?key=dg679d8sg69sd7f6g9 where the 'key' attribute is an arbitrrary local key you set in the script (NOT your API key).
