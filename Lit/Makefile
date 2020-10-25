
all: tex_vers_internall
clean: tex_vers_internclean
cleanall: tex_vers_interncleanall

MAKEDIR = $(FIGURESDIR)/generic-Makefiles/
RULES = $(MAKEDIR)/figures.Makefile-rules.mk
RULES_TEX_VERSION = $(MAKEDIR)/tex_version.Makefile-rules.mk
GLOBALDEPS = $(MAKEDIR)/figures.Makefile-globaldep.mk
GLOBALDEPS_TEX_VERSION = $(MAKEDIR)/tex_version.Makefile-globaldep.mk
SUBDIRSEXCLUDE=Figures SingleSlides

include elib-link-list


STDPSTEX=
STDEEPIC=
STDLATEX=
CONVERT=
DRAFTS=no
SUBCLIPSDIM=

ALLCONVERT= no
ALLCOMPRESSED=yes
COMPRESSEDFORMATS=

ALLTEXPDF=no
# TEXPS=
# TEXPDF=

VERSION_FOR_FILES=
VERSION_SEP=+++

include $(RULES)
include $(GLOBALDEPS)

include $(RULES_TEX_VERSION)
include $(GLOBALDEPS_TEX_VERSION)


