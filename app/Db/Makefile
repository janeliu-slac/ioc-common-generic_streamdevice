TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install)
# databases, templates, substitutions like this
DB_INSTALLS += $(IOCADMIN)/db/iocSoft.db
DB_INSTALLS += $(AUTOSAVE)/db/save_restoreStatus.db
DB_INSTALLS += $(ASYN)/db/asynRecord.db
DB += gsd.db

#----------------------------------------------------
# Create and install (or just install)
# Archive files, templates, substitutions like this
#
# SLAC EPICS Base archive rule expects a .sub-arch input when generating a 
# .archive file.
ARCHIVE += gsd.archive

#----------------------------------------------------
# Create and install (or just install)
# Autosave request files, templates, substitutions like this
#
# SLAC EPICS Base autosave rule expects a .sub-req input when generating a 
# .req file. The rule is $(COMMON_DIR)/%.req %.req: %.sub-req
REQ += gsd.req

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE
