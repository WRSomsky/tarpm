# tarpm <br><sub><sup> Build RPM packages for file deployment

`tarpm` is a wrapper around `rpmbuild`
which assists in creating "binary" RPMs
for distributing files w/in a site.
It has features for overwriting files owned by other RPM packages
making it useful for distributing system configuration files
as discussed in
[System Configuration via RPM](https://wrsomsky.github.io/blog/0006/).
It also adds several *ease-of-use* features
somewhat simplifying the writing
of the required RPM Spec files.

