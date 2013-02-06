Packages
========

Repository of Erlang tools, libraries and applications.

The goal of this project is to provide an index of existing projects
that any dependency or package management tool can use.

File Format
-----------

Packages use the Erlang `file:consult/1` format. It is a list of
named tuples. The definition of the fields follow.

You can use this empty template as a basis for creating more
packages. Please look at existing packages if you are not sure
on how to do something.

``` erlang
{name, ""}.
{description, ""}.
{license, ""}.
{source, git, ""}.
{otp_versions, ["R15"]}.
{links, [
	{"", ""}
]}.
```

Required Fields
---------------

 *  `name`: The name of the project. Example: "Cowboy".
 *  `description`: A short one line description of the project.
 *  `license`: The license used by the project. See below.
 *  `source`: A method and a link to retrieve the source from.
 *  `otp_versions`: The list of supported Erlang/OTP versions.

Optional Fields
---------------

 *  `alternates`: A list of alternative versions of this project.
 *  `links`: A list of links related to the project.

Links can be the "Project page", "User guide", "Function reference",
"Commercial support" or anything else useful for understanding the
project.

Licenses
--------

This is a list of licenses with projects in this repository, with
a link to said licenses.

 *  [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
 *  [EPL 1.1](http://www.erlang.org/EPLICENSE)
 *  [ISC](http://opensource.org/licenses/isc-license.txt)
 *  [MIT](http://opensource.org/licenses/MIT)
 *  Proprietary

Some projects may not come with a license, or may come with a license
we cannot find information about. These include:

 *  DWTFYW License
