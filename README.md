# xmlsec-rebundled

This rebundles `org.apache.santuario:xmlsec` to include the dependencies from `org.glassfish.metro:webservices-extra-xmlsec` without exporting them. This is meant to replace the `xmlsec` and `webservices-extra-xmlsec` modules in Payara 6, where the `slf4j-api` export from `webservices-extra-xmlsec` can prevent applications loading their slf4j implementation.
