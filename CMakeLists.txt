#
# Copyright Troy D. Straszheim
#
# Distributed under the Boost Software License, Version 1.0.
# See http://www.boost.org/LICENSE_1_0.txt
#

# Add a library target to the build system
ryppl_library_project(
  boost.serialization
  SRCDIRS  src
  TESTDIRS  test
  #  DOCDIRS 
  DESCRIPTION  "Serialization for persistence and marshalling."
  AUTHORS  "<ramey -at- rrsd.com>"
  #  MAINTAINERS 
)


