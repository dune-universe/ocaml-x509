0.2.0 (2014-10-30):
* expose Certificate.cert_hostnames, wildcard_matches
* Certificate.verify_chain_of_trust and X509.authenticate both return now
  [ `Ok of certificate | `Fail of certificate_failure ], where [certificate] is the trust anchor

0.1.0 (2014-07-08):
* initial beta release