# str2file
quickly create files from a space-delimited string of file names

* **Organization** [Karbon Industries][companyURL]
* **Author** [Shammel Lee][authorURL]
* **Start Date** Wed Dec  3 15:24:25 EST 2014

[companyURL]: http://karbonindustri.es
[authorURL]: http://www.shammellee.com/

# usage
	$ str2file "[f:,d:] <filename> ..."

# examples
	# create files named `foo.txt`, `bar.txt`, and `baz.txt`
	$ str2file "f: foo.txt bar.txt baz.txt"

	# `f:` is optional for creating files
	$ str2file "foo.txt bar.txt baz.txt"

	# create directories named `foo`, `bar`, and `baz`
	$ str2file "d: foo bar baz"
