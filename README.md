# OpenActive Data Profiles

JSON Schema files defining three OpenActive data profiles:

* Core (powering activity finders)
* Social Prescribing
* Accessibiity

## Profile self-containment

Note that, despite their considerable commonalities, the various profiles do not cross-reference each other. This is to preserve the possibility of divergence between the profiles (as seen, for instance, with the different profiles of `activity` between the Social Prescribing and Core profiles). **The profiles should thus be treated as self-contained and independent, with no references linking them to each other.**

## TODOs

* most constraints right now are only on string-length. These should be tightened into regexes where possible
* Add 'description' documentation to the Schema files
* Think about the implications of the different profiles for different processing chains. Should the normaliser ideally produce a superset valid against all profiles?
