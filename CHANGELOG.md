10/11/2018 12:55  1.1.0  Add support for certificate revocation and ECDSA certificates
6933ffb Merge pull request #141 from jderusse/ecdsa
f7bac9e Fix undefined const OPENSSL_KEYTYPE_EC
5cf1a8d Add DH and DSA generators
c22cd9e Add support for ECDSA
3881f18 Merge pull request #143 from jderusse/update-phpunit
2cf3baf Use simple-phpunit to run tests
5194897 Merge pull request #142 from jderusse/fix-deps
4f13320 Add missing dependencies in composer.json files
da7c0e1 Merge pull request #139 from acmephp/revoke-certificate
39cf7fa Fix certificate revocation
27d4355 Update test to pass with Pebble implementation
94e2f20 Remove Certificate::__toString(), Command validation failure warning -> error
ef00e5f Add revocation reason and more helpful doc
c61019c Fix cs issues
7418bd9 Add api for certificate revocation
6d3888e Merge pull request #140 from acmephp/remove-scrutinizer
29258e6 Remove Scrutinizer
61df472 Merge pull request #138 from acmephp/remove-config-platform
af56ed7 Remove config.platform.php in Composer
e8029c2 Bump to dev
27/10/2018 12:07  1.0.1  Fix PHP version issue
6079833 Merge pull request #137 from acmephp/fix-php-version
6d6e2d2 Fix tests configuration
12ed5fc Fix PHP version in composer.json
958d497 Remove Gitter
a4effb8 Add link to core and ssl libraries in README
b17236e Bump to dev
14/10/2018 12:05  1.0.0  First stable release
1e4ba50 Merge pull request #135 from acmephp/prepare-release
13866eb Update README
9d773bb Remove beta messages
25e986e Prepare stable release, use only PrettyCI and fix CS
6267095 Merge pull request #134 from ScullWM/patch-1
542ed28 Fix markdown error
c90e0a8 Merge pull request #132 from jderusse/optimize-route53
c6b767a Optimize Route53 resolution
d4d2fa6 Merge pull request #131 from jderusse/catch-unresolvabled-nameserver
d57be04 Merge pull request #130 from alexmckinnon/csr-payload
1fd6427 Add common name to CSR payload
95f30c4 atch case where NameServer is not resolvable
421a4ab Merge pull request #128 from jderusse/update-dependencies
cdde24e Update dependencies
9b8ae4c Merge pull request #127 from jderusse/improve-libdns-fetching
d553270 Improve DNS checking
93bf725 Merge pull request #126 from jderusse/catch-libdns-exception-2
c40f93b Catch exception on external calls
9bdd3ed Merge pull request #125 from jderusse/catch-libdns-exception
1930de5 Wrap external call in try/catch block
03b5532 Merge pull request #123 from jderusse/fix-status
c2b6b8d Allow "ready" status for orders with valid challenges
f039226 Merge pull request #119 from acmephp/auto-split
9ea70bc Automate split
32ccf3f Merge pull request #120 from jderusse/refactor-travis
2b5b296 Add comments
9b7ea2b Switch to travis pipeline
bbe4b9b Merge pull request #116 from jderusse/fix-sftp-config
db6c434 Merge pull request #115 from jderusse/fix-missing-lib
db391fc Add lib-xml used by SFTP adapter
922bd70 Fix typo in config
4a08ccc Merge pull request #113 from jderusse/fix-route53-domain-lookupx
bce7338 Fix Route53 zone search
c08891c Merge pull request #109 from jderusse/optimize-resolve
5dddf23 Optimize Route53 solvin
166dde3 Merge pull request #112 from kirtangajjar/fix-nginxproxy-wildcard
a848329 Merge pull request #111 from kirtangajjar/fix-nginxproxy-crt-generation
01f00c8 Merge pull request #107 from jderusse/feature-improve-error-messages
34bd808 Merge pull request #108 from jderusse/fix-payload
ca6531f Fix nginxproxy wildcard certificates
bac8140 Fixed in a bit better way
d081953 Fix nginxproxy crt generation
09ff221 Remove non linear index on array
26e672a Improve error messages
74dd66d Merge pull request #104 from benjilevens/laravel-5.5
55d7b9b Merge pull request #106 from benjilevens/jose-json
2dd3303 Merge pull request #102 from jderusse/feature-skip-challenge
d4dcd9f Merge pull request #105 from benjilevens/request-certificate-calling-finalize-order
503c4df Use more appropriate Accept and Content-Type headers
475f359 Support multiple versions of swift mailer
4b9dac7 Make requestCertificate call finalizeOrder with required parameters
005081d Bump Swiftmailer version to prevent composer conflicts when installing into a Laravel 5.5 project
82e5e5b Skip challenge when no renewal
fd54a08 Merge pull request #101 from jderusse/feature-multiple-challenges
dd88adc Optimize challenge solving by solving several challenges at once
0e618e3 Merge pull request #100 from jderusse/feature-file-solver
898c939 Use service locator
04c9814 Add a filesystem solver (to upload http challenge)
9818d39 Merge pull request #98 from jderusse/fix-tree
208913f Refactor file tree
4966d60 Merge pull request #96 from jderusse/fix-combined-public
1671a5b Merge pull request #97 from jderusse/fix-status-expired
e327321 Add an option to hide/show expired certificates
51ebab0 Move combined certificate in private folder
bd1478e Merge pull request #95 from jderusse/fix-ci
a08cb2e Fix CS
1d590bb Switch from styleCi to travis
477929d Merge pull request #94 from jderusse/fix-debug
75552fd Remove debug
c4b8c66 Merge pull request #87 from jderusse/feature/run
38e49cb Add a run command
15c1809 Merge pull request #93 from jderusse/feature/docker
9907669 Add a dockerfile
a7b8581 Merge pull request #92 from jderusse/v2
1550972 Implement v2 protocol
6d15380 Implement ELB installation
3c8b06a Add Route53 solver
f306733 Bump to dev
21/01/2018 18:31  1.0.0-beta5  Fix deprecations and allow setting KeyPair from Client object
466e009 Release of new version 1.0.0-beta5
0a94b15 Fix mailer handler
8fde026 Allow setting KeyPair from Client object (#72)
e2ac2bf Fix json_decode error handling in SecureHttpClient and ServerErrorHandler
4c7d10d Fix deprecations and improve tests
f559a93 [doc] Fix typo on README
0b4ea8b Bump to dev
21/01/2018 18:23  1.0.0-beta5  Fix deprecations and allow setting KeyPair from Client object
0a94b15 Fix mailer handler
8fde026 Allow setting KeyPair from Client object (#72)
e2ac2bf Fix json_decode error handling in SecureHttpClient and ServerErrorHandler
4c7d10d Fix deprecations and improve tests
f559a93 [doc] Fix typo on README
0b4ea8b Bump to dev
* 1.0.0-beta4 (2017-01-29)

 * 0b18a86 Redone nameing of ::getResource with new tests (#61)
 * 78d0e2d Accept empty issuer CN field (#59)
 * 9d434e8 Certificate::getPublicKey and ::getResource (#58)
 * 3f2b652 Added new methods for DER formatted keys and HPKP hash generation (#56)
 * c6bb3c1 Merge pull request #55 from jankal/master
 * f0118ff Get public key from private key
 * ff75825 Merge pull request #49 from Sh1nto/Fix-hashtag-in-default-config-slack-channel-name
 * 3c072c3 remove the hashtag of slack channel name in the default config
 * 529d5eb Merge pull request #45 from acmephp/strict-equals
 * 43f7a45 Add SensioLabsInsight analysis
 * 16bc374 Merge pull request #44 from acmephp/fix-vendor-bin
 * ea11bca Merge pull request #43 from acmephp/update-phpunit
 * 97a8b70 Update PHPUnit and simplify SFTP tests
 * a7f194a Fix vendor/bin/acme autoload path
 * 5e4a887 Bump to dev

* 1.0.0-beta3 (2016-12-09)

 * daa6d1c Merge pull request #40 from acmephp/fix-39
 * 0b8629e Remove RECOVER_REGISTRATION obsolete unused resource
 * de625cb Merge pull request #35 from acmephp/fix-34
 * a7973dc Fix #34 by removing illogical data validation in resources directory
 * 3a77a61 Merge pull request #31 from acmephp/rancher
 * 831f3ca Implement Push to Rancher post-generate action
 * 09437a7 Merge pull request #30 from acmephp/verbosity
 * 794f8d5 Introduce CLI logger to handle different verbosities properly
 * e055695 Bump to dev

* 1.0.0-beta2 (2016-10-19)

 * ed2cc9e Update main and components README files
 * 1adff0d Improve some commands descriptions
 * b727bd3 Merge pull request #29 from acmephp/fix-scrunitizer
 * a774fa1 Decrease code complexity by splitting complex methods into smaller ones
 * 5a72637 Improve readability of monitoring handlers
 * 2c88554 Merge pull request #25 from jderusse/custom-challenger
 * a4bfd2f Create fullchain certificate in nginx-proxy action
 * 93be223 Update version to dev
 * d5f60c6 Use container's tag to easily extends solvers
 * 914f33b Small fixes
 * 6d678dd Small fixes
 * ee753c1 Add tests
 * 2aa1b9d Separate validators from solvers
 * 0e46137 Fix tests
 * 297b724 Add automatic pre-validation
 * 40311b3 Remove data extractor from solvers
 * 6305409 Fix CS
 * 1d1bf00 Rename challenger into SOlver
 * e1289df Allow custom challenger extension

* 1.0.0-beta1 (2016-09-24)

 * f1585a4 Fix type in README
 * 54d68c3 Merge pull request #24 from jderusse/multi-domains
 * 8553f5c Split method firstRequest to reduce complexity
 * bf79270 Improve status's display
 * 7bd4e79 Separate domain and alternativeNames
 * 5a44496 Allow multi-domain in cli
 * f7de82d Automatically agreed with agrement (#26)
 * 7accf30 Fix tests (#27)

* 1.0.0-alpha10 (2016-08-16)

 * 3bfa96c Update RegisterCommand.php (#21)
 * d3d779f Bump version

* 1.0.0-alpha9 (2016-07-27)

 * 3e89b38 Remove unsupported actions from the dist file for the moment
 * 07857e6 Add PHP 7.1 in Travis and improve CI configuration (#19)
 * dfcfdd5 Implement monitoring system with email and slack handler (#16)
 * adf4dc8 Update version as DEV
 * f61df6f Fix Guzzle URI test (#17)
 * 846bbce Fix assertions messages
 * 113b2d8 Fix 404 on documentation link (#15)