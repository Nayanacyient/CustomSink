ossieName = CustomSink
bindir = $(prefix)/dom/components/rh/CustomSink/cpp/
bin_PROGRAMS = CustomSink

xmldir = $(prefix)/dom/components/rh/CustomSink/
dist_xml_DATA = ../CustomSink.scd.xml ../CustomSink.prf.xml ../CustomSink.spd.xml
ACLOCAL_AMFLAGS = -I m4 -I${OSSIEHOME}/share/aclocal/ossie
AUTOMAKE_OPTIONS = subdir-objects



distclean-local:
	rm -rf m4
	rm -f config.*
	rm -rf autom4te.cache
	rm -f acinclude.m4
	rm -f aclocal.m4
	rm -f configure
	rm -f depcomp
	rm -f install-sh
	rm -f ltmain.sh
	rm -f Makefile.in
	rm -f missing
	rm -rf .deps


# Sources, libraries and library directories are auto-included from a file
# generated by the REDHAWK IDE. You can remove/modify the following lines if
# you wish to manually control these options.
include $(srcdir)/Makefile.am.ide
CustomSink_SOURCES = $(redhawk_SOURCES_auto)
CustomSink_LDADD = $(SOFTPKG_LIBS) $(PROJECTDEPS_LIBS) $(BOOST_LDFLAGS) $(BOOST_THREAD_LIB) $(BOOST_REGEX_LIB) $(BOOST_SYSTEM_LIB) $(INTERFACEDEPS_LIBS) $(redhawk_LDADD_auto)
CustomSink_CXXFLAGS = -Wall $(SOFTPKG_CFLAGS) $(PROJECTDEPS_CFLAGS) $(BOOST_CPPFLAGS) $(INTERFACEDEPS_CFLAGS) $(redhawk_INCLUDES_auto)
CustomSink_LDFLAGS = -Wall $(redhawk_LDFLAGS_auto)

