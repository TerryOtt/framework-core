# vim: noet: softtabstop=0

xmldir = $(prefix)/dom/components/ECM_PY/
dist_xml_DATA = ../ECM_PY.scd.xml ../ECM_PY.prf.xml ../ECM_PY.spd.xml
domdir = $(prefix)/dom/components/ECM_PY/python/

distclean-local:
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

# Sources are auto-included from a file generated by the REDHAWK IDE. You may
# remove the following lines if you wish to manually control these options.
include $(srcdir)/Makefile.am.ide
nobase_dist_dom_SCRIPTS = $(redhawk_SCRIPTS_auto)
nobase_dist_dom_DATA = $(redhawk_DATA_auto)
