Semantic Identity Comparison
============================

| [vCard 4.0][VCARD4]   | [vCard Ontology (2006)][VCARD RDF 2006] | [vCard Ontology (2014)][VCARD RDF 2014] | [W3C PIM][W3C PIM]    | [FOAF][FOAF] | [schema.org Person][SCHEMA PERSON] | [NEPOMUK Contact][NEPOMUK CONTACT] | [Portable Contacts][PORTABLE CONTACTS] | [hCard][UF HCARD]       | [h-card][UF H-CARD] | [LDAP inetOrgPerson][INETORGPERSON] |
| --------------------- | --------------------------------------- | --------------------------------------- | --------------------- | ------------ | ---------------------------------- | ---------------------------------- | -------------------------------------- | ----------------------- | ------------------- | ----------------------------------- |
| Family Name           | family-name                             | hasFamilyName                           | familyName            | familyName   | familyName                         | nameFamily                         | familyName                             | family-name             | p-family-name       | sn                                  |
| Given Name            | given-name                              | hasGivenName                            | givenName             | givenName    | givenName                          | nameGiven                          | givenName                              | given-name              | p-given-name        | givenName                           |
| Additional Name       | additional-name                         | hasAdditionalName                       | middleName            | ~            | additionalName                     | nameAdditional                     | middleName                             | additional-name         | p-additional-name   | ~                                   |
| Honorific Prefix      | honorific-prefix                        | hasHonorificPrefix                      | personalTitle         | title        | honorificPrefix                    | nameHonorificPrefix                | honorificPrefix                        | honorific-prefix        | p-honorific-prefix  | title (?)                           |

[FOAF]: http://xmlns.com/foaf/spec/
[INETORGPERSON]: http://tools.ietf.org/html/rfc2798
[NEPOMUK CONTACT]: http://www.semanticdesktop.org/ontologies/2007/03/22/nco/
[PORTABLE CONTACTS]: http://portablecontacts.net/draft-spec.html
[SCHEMA PERSON]: https://schema.org/Person
[UF HCARD]: http://microformats.org/wiki/hcard
[UF H-CARD]: http://microformats.org/wiki/h-card
[W3C PIM]: http://www.w3.org/2000/10/swap/pim/contact
[VCARD RDF 2006]: http://www.w3.org/2006/vcard/ns
[VCARD RDF 2014]: http://www.w3.org/TR/vcard-rdf/
[VCARD4]: http://tools.ietf.org/html/rfc6350
